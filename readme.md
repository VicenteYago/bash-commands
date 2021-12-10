* **scp** : 
  
  Transfers files from remote to local dir
  ```{bash}
  scp REMOTE_USER@IP:REMOTE_ROUTE LOCAL_DIR
  scp REMOTE_USER@IP:REMOTE_ROUTE ./
  ```

* **pkill**

  https://stackoverflow.com/questions/8987037/how-to-kill-all-processes-with-a-given-partial-name* 
  
  Kills a process which names matchs a pattern
  ```{bash}
  pkill -f my_pattern
  pkill -f -9 my_pattern
  ```
