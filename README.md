# mutt_tips: Modern IMAP / mutt for Productivity

Tips and cheatsheet for productive mutt use.
[@jpdaigle](https://twitter.com/jpdaigle)

---

## Config
*TODO* IMAP configs compatible with Apple `mail.app`

*TODO* talk about gpg + password file for password loading

---

## Keys and Batch-Processing
### Moving Around
   * `shift+*` jump to last message
   * `c, ?` change folder, from list
   * `i` back to list from a message
   
### Filtering display
`l` enables a display filter. From there, use an expression to filter the list.

   * `~s <subject expression>` by subject expression
   * `~N` NEW flag only
   * `~f <from>` from expression
   * `~d <date expression>` by date

### Actions
   * `T` tag with last filter
   * `;` tag-prefix: next command applies to TAGGED messages
   
