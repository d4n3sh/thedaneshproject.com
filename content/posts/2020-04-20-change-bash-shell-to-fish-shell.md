---
title: Change BASH shell to FISH shell
author: Danesh
type: post
date: 2020-04-20T10:25:59+00:00
url: /posts/change-bash-shell-to-fish-shell/

---
I used the change shell command _**chsh**_ to change the default shell environment for my id from [BASH][1] to the [FISH][2] shell.

<pre class="wp-block-code"><code>>- &#91;danesh.manoharan@workstation ~]$ chsh 
Changing shell for danesh.manoharan. 
New shell &#91;/bin/bash]: /usr/bin/fish 
Password: 
Shell changed. 

>_ chsh -s /usr/bin/fish 
Changing shell for danesh.manoharan. 
chsh: Shell changed. </code></pre>

 [1]: https://www.gnu.org/software/bash/
 [2]: https://fishshell.com/