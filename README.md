# gdrive-bash

this two scripts provide a git-like pull/push procedures but only head contained.

`gdrive` can be found at https://github.com/prasmussen/gdrive



# How to use

1. Assume that you have a directory, say `mehome` . And you want to keep exactly the same with your remote directory on google drive, say `rmhome`.  If you want, the following command is easy for you to use

   ```bash
   > gdrive mkdir rmhome
   ```

2. Once you created a directory. copy the file id into your `.gdrive/configure`  and put it at the first line of this file. At the second line of `.gdrive/configure`, you can specify a directory that used as a cache. e.g.

   ```bash
   0BxdsfgtgasdafdsDSAcdsafDAFGDS
   /h/.gdrive_local
   ```

   ​

3. push your current content

   ```bash
   > bash gdrive-push
   ```

   Please note that this command will remove any content that exist on your remote repository but not exist in your local repository.

   ​

4. pull your remote files into your local directory

   ```bash
   > bash gdrive-pull
   ```



# Contact

Please open a issue for bugs.

