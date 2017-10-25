# Xenomorphales licensing model

## For libraries/reusable CAD parts

Our libraries (software bits) and reusable CAD parts (mechanical and electronic
design files) shared by several of our project must be licensed under the terms
of the BSD 3-clause license.

## For end products

Our end products (simulation software, robot's specific software, mechanical
design and electronic design) must be licensed under the terms of the GNU
General Public License version 3.

## Instantiating a new project

1. When creating a new libraries (reusable CAD parts should use the xenocad
   repository), the first commit have to create the README.md file and the
   LICENSE.md file which must be a copy of bsd3.md file. The year on the
   copyright notice must be filled in appropriately. The license must also be
   featured at the beginning of source files.
2. When creating a new end product, the first commit have to create the
   README.md file and the LICENSE.md file which must be a copy of gplv3.md
   file. The license notice (see _How to Apply These Terms to Your New Programs_
   chapter in the GPLv3 license) must also be featured at the beginning of
   soure files with the appropriate year and Xenomorphales as author.

## Credits

- [TheFox/GPLv3.md](https://github.com/TheFox/GPLv3.md) (commit c81a2af):
  for a Markdown version of the GPLv3 more readable on GitHub.
