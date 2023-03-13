# aspirantes-mir-ejercicio-bonus
Administrador@AM-39 MINGW64 ~ (master)
$ git clone
fatal: You must specify a repository to clone.

usage: git clone [<options>] [--] <repo> [<dir>]

    -v, --verbose         be more verbose
    -q, --quiet           be more quiet
    --progress            force progress reporting
    --reject-shallow      don't clone shallow repository
    -n, --no-checkout     don't create a checkout
    --bare                create a bare repository
    --mirror              create a mirror repository (implies bare)
    -l, --local           to clone from a local repository
    --no-hardlinks        don't use local hardlinks, always copy
    -s, --shared          setup as shared repository
    --recurse-submodules[=<pathspec>]
                          initialize submodules in the clone
    --recursive ...       alias of --recurse-submodules
    -j, --jobs <n>        number of submodules cloned in parallel
    --template <template-directory>
                          directory from which templates will be used
    --reference <repo>    reference repository
    --reference-if-able <repo>
                          reference repository
    --dissociate          use --reference only while cloning
    -o, --origin <name>   use <name> instead of 'origin' to track upstream
    -b, --branch <branch>
                          checkout <branch> instead of the remote's HEAD
    -u, --upload-pack <path>
                          path to git-upload-pack on the remote
    --depth <depth>       create a shallow clone of that depth
    --shallow-since <time>
                          create a shallow clone since a specific time
    --shallow-exclude <revision>
                          deepen history of shallow clone, excluding rev
    --single-branch       clone only one branch, HEAD or --branch
    --no-tags             don't clone any tags, and make later fetches not to follow them
    --shallow-submodules  any cloned submodules will be shallow
    --separate-git-dir <gitdir>
                          separate git dir from working tree
    -c, --config <key=value>
                          set config inside the new repository
    --server-option <server-specific>
                          option to transmit
    -4, --ipv4            use IPv4 addresses only
    -6, --ipv6            use IPv6 addresses only
    --filter <args>       object filtering
    --also-filter-submodules
                          apply partial clone filters to submodules
    --remote-submodules   any cloned submodules will use their remote-tracking branch
    --sparse              initialize sparse-checkout file to include only files at root
    --bundle-uri <uri>    a URI for downloading bundles before fetching from origin remote


Administrador@AM-39 MINGW64 ~ (master)
$ git clone https://github.com/YesiTamayo/aspirantes-mir-ejercicio-1/blob/main/LICENSE.md
Cloning into 'LICENSE.md'...
fatal: repository 'https://github.com/YesiTamayo/aspirantes-mir-ejercicio-1/blob/main/LICENSE.md/' not found

Administrador@AM-39 MINGW64 ~ (master)
$

Administrador@AM-39 MINGW64 ~ (master)
$ git clone ^[[200~https://yesitamayo-symmetrical-bassoon-v95q5ggr9vw3qqp.github.dev/~

Administrador@AM-39 MINGW64 ~ (master)
$ git clone ^[[200~https://yesitamayo-symmetrical-bassoon-v95q5ggr9vw3qqp.github.dev/~

Administrador@AM-39 MINGW64 ~ (master)
$ git clone ^[[200~https://yesitamayo-symmetrical-bassoon-v95q5ggr9vw3qqp.github.dev/~

Administrador@AM-39 MINGW64 ~ (master)
$ git clone ^[[200~https://yesitamayo-symmetrical-bassoon-v95q5ggr9vw3qqp.github.dev/~
Cloning into '~'...
fatal: protocol '?[200~https' is not supported

Administrador@AM-39 MINGW64 ~ (master)
$

Administrador@AM-39 MINGW64 ~ (master)
$ git clone https://yesitamayo-symmetrical-bassoon-v95q5ggr9vw3qqp.github.dev/
Cloning into 'yesitamayo-symmetrical-bassoon-v95q5ggr9vw3qqp.github.dev'...
fatal: unable to update url base from redirection:
  asked for: https://yesitamayo-symmetrical-bassoon-v95q5ggr9vw3qqp.github.dev/info/refs?service=git-upload-pack
   redirect: https://github.com/login?return_to=https%3A%2F%2Fgithub.com%2Fcodespaces%2Fyesitamayo-symmetrical-bassoon-v95q5ggr9vw3qqp

Administrador@AM-39 MINGW64 ~ (master)
$

Administrador@AM-39 MINGW64 ~ (master)
$ git clone https://github.com/YesiTamayo/aspirantes-mir-ejercicio-2
Cloning into 'aspirantes-mir-ejercicio-2'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

Administrador@AM-39 MINGW64 ~ (master)
$ cd aspirantes-mir-ejercicio-2

Administrador@AM-39 MINGW64 ~/aspirantes-mir-ejercicio-2 (main)
$ git branch nueva-funcionalidad

Administrador@AM-39 MINGW64 ~/aspirantes-mir-ejercicio-2 (main)
$ git checkout -b nueva-funcionalidad
fatal: a branch named 'nueva-funcionalidad' already exists

Administrador@AM-39 MINGW64 ~/aspirantes-mir-ejercicio-2 (main)
$ touch nuevo-archivo.txt

Administrador@AM-39 MINGW64 ~/aspirantes-mir-ejercicio-2 (main)
$ nano nuevo-archivo.txt

Administrador@AM-39 MINGW64 ~/aspirantes-mir-ejercicio-2 (main)
$ git add nuevo-archivo.txt
warning: in the working copy of 'nuevo-archivo.txt', LF will be replaced by CRLF the next time Git touches it

Administrador@AM-39 MINGW64 ~/aspirantes-mir-ejercicio-2 (main)
$ git commit -m "Agregado nuevo archivo para la nueva funcionalidad"
[main cb32940] Agregado nuevo archivo para la nueva funcionalidad
 1 file changed, 7 insertions(+)
 create mode 100644 nuevo-archivo.txt

Administrador@AM-39 MINGW64 ~/aspirantes-mir-ejercicio-2 (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Administrador@AM-39 MINGW64 ~/aspirantes-mir-ejercicio-2 (main)
$ cat nuevo-archivo.txt
<?php
        session_start();
        include_once 'model/conexion.php';
        $usuario = $_POST['txtUsu'];
        $contrasena = $_POST['txtPass'];
        $sentencia = $bd->prepare('select * from t_usuario where
                                                                nombre_usu = ? and password_usu = ?;');

Administrador@AM-39 MINGW64 ~/aspirantes-mir-ejercicio-2 (main)
$ git merge nueva-funcionalidad
Already up to date.

Administrador@AM-39 MINGW64 ~/aspirantes-mir-ejercicio-2 (main)
$ cat nuevo-archivo.txt
<?php
        session_start();
        include_once 'model/conexion.php';
        $usuario = $_POST['txtUsu'];
        $contrasena = $_POST['txtPass'];
        $sentencia = $bd->prepare('select * from t_usuario where
                                                                nombre_usu = ? and password_usu = ?;');

Administrador@AM-39 MINGW64 ~/aspirantes-mir-ejercicio-2 (main)
$
