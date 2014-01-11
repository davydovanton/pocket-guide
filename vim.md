## Normal mode

### Navigate inside files

|  Command  |                     Effect (Move cursor)                          |
|:----------|:------------------------------------------------------------------|
|    *j*    | Down one real line                                                |
|    *k*    | Up one real line                                                  |
|    *h*    | Left one symbol                                                   |
|    *l*    | Right one symbol                                                  |
|    *0*    | To first chracter of real line                                    |
|    *^*    | To first nonblank character of real line                          |
|    *$*    | To end of real line                                               |
|    *gj*   | Down one display line                                             |
|    *gk*   | Up one display line                                               |
|    *g0*   | To first chracter of display line                                 |
|    *g^*   | To first nonblank character of display line                       |
|    *g$*   | To end of display line                                            |
|    *w*    | Forward to start of next word                                     |
|    *b*    | Backward to start of current/previous word                        |
|    *e*    | Forward to end of current/next word                               |
|    *ge*   | Forward to end of previous word                                   |
| *f{char}* | Forward to the next occurrence of {char}                          |
| *F{char}* | Backward to the previous occurrence of {char}                     |
| *t{char}* | Forward to the character defore the next occurrence of {char}     |
| *F{char}* | Backward to the character after the previous occurrence of {char} |
|    *;*    | Repeat the last character-search command                          |
|    *,*    | Reverse the last character-search command                         |
