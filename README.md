# xpdp1_install_docs

Unofficial install guide for XPDP1 and the XPD family of codes. XPDP1 and the XPD family is written and owned by PTSG (https://ptsg.egr.msu.edu/). All credit for the software itself and its development is theirs. Technical support for the software itself, as well as issues encountered while installing it for later editions of Ubuntu than is covered in the current edition of this work should also be addressed to PTSG.

## Building

Creating a PDF copy of `xpdp1_install_guide_LINUX.tex` or `xpdp1_install_guide_WSL.tex` can be done in any LaTeX production system. General steps for this are shown below:

1) Download and install a LaTeX distribution (TeX Live or MikTeX are good choices for Windows, MacTeX for MacOS, and many more exist...).
2) If you want to build the guides using a visual environment, ensure that your distribution came with one or download one (a good option for first-time users is TeXstudio, another good option is TeXworks).
3) Build the document:

   * If you are using a visual environment, refer to the build instructions that come with that program.

   * If you are using the terminal (in Linux or MacOS) or command prompt (Windows), use the following command in the directory where the .tex file you want to compile is located, replacing `file_sample_name` with the name of the file you want to compile:

      ```
      pdflatex -synctex=1 -interaction=nonstopmode "file_sample_name".tex
      ```

      If an issue is encountered with the above command, try `pdflatex --help` to ensure the right command flags are being used or search any LaTeX forum for more detailed troubleshooting instructions.

## Contributing

If you would like to contribute to updates on the install guide, please fork the repository, clone your fork, create a branch, make and commit your changes, push your changes back up to GitHub, and make a pull request.
