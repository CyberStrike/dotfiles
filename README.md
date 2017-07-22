1. Use [Dotbot](https://github.com/anishathalye/dotbot) to install.

  ```shell
  git clone $url && cd dotfiles && ./install
  ```

2. Install Atom Packages from the list.

  ```shell
  apm install --packages-file atom-packages.list
  ```
3. Once in awhile you have to backup your atom-packages.
   Sadly atom doesn't store this in an external file already.
   Since there is no standard storage location for atom plugin configuration,
   you may have to reconfigure somethings.

  ```shell
  apm list --installed --bare > atom_packages.list
  ```
