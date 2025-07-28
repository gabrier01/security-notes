
| Webmail                | Path(s) comuns                             | Observações                                                   |
| ---------------------- | ------------------------------------------ | ------------------------------------------------------------- |
| **Roundcube**          | `/roundcube/`, `/webmail/`, `/mail/`       | Um dos mais populares                                         |
| **SquirrelMail**       | `/squirrelmail/`, `/webmail/`              | Interface antiga, mas ainda usada em alguns sistemas legados. |
| **RainLoop**           | `/rainloop/`, `/webmail/`, `/mail/`        | Possui painel admin exposto via `/?admin`.                    |
| **Horde Webmail**      | `/horde/`, `/webmail/`                     | Complexo e vulnerável em versões antigas                      |
| **Zimbra**             | `/zimbra/`, `/zimbra/mail`, `/zimbraAdmin` | Suite corporativa. Painel admin é alvo comum.                 |
| **iRedMail**           | `/iredadmin/`, `/mail/`, `/webmail/`       | Baseado em Roundcube e Postfix/Dovecot.                       |
| **AfterLogic WebMail** | `/webmail/`, `/afterlogic/`                | Tem versão lite (open source). Path `/adminpanel` possível.   |
| **Axigen WebMail**     | `/webmail/`, `/axigen/`, `/admin/`         | Componente pago. Porta 9000 para admin em alguns setups.      |
| **Mailcow**            | `/SOGo/`, `/webmail/`, `/admin/`           | Usa SOGo como frontend, sistema moderno em containers.        |

# Wordlist
Wordlist simples para bruteforce de webmail:

```
/roundcube/
/squirrelmail/
/webmail/
/mail/
/horde/
/rainloop/
/zimbra/
/iredadmin/
/afterlogic/
/sogo/
/admin/
/?admin
```