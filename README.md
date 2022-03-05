This repository contains source codes for the "Julia for Data Analysis" book
that is written by Bogumił Kamiński and is planned to be published in 2022 by
[Manning Publications Co.](https://www.manning.com/).

In order to prepare the Julia environment before working with the materials
presented in the book please perform the following setup steps:
* [download](https://julialang.org/downloads/) and
  [install](https://julialang.org/downloads/platform/)
  [Julia](https://julialang.org/);
  all the codes were tested under Julia 1.7;
* make sure you can start Julia by running `julia` command in your system shell
  (alternative ways to use Julia are described in Appendix A to the book)
* download [this repository](https://github.com/bkamins/JuliaForDataAnalysis)
  to a local folder on your computer;
* start Julia in a folder containing the downloaded material using the command
  `julia --project`; the folder must
  contain the Project.toml and Manifest.toml files prepared for this book
  (an explanation what these files do and why they are required is given in
   Appendix A to the book);
* press *]*, write `instantiate` and press *Enter* (this process will ensure
  that Julia properly configures the working environment for working with
  the codes from the book);
* press *Backspace*, write `exit()` and press *Enter*; now you should exit Julia
  and everything is set up to work with the materials presented in the book.

The codes for each chapter are stored in files named *chXX.jl*, where *XX* is
chapter number.

Solutions to the exercises that are presented in appendix B in
the book are stored in *appB.jl* file. These solutions assume that they are
executed in the same Julia session as the codes from the chapter where the
question was posted (so that appropriate variables and functions are defined
and appropriate packages are loaded).

To work with codes from some given chapter:
* start a fresh Julia session using the `julia --project` command in a folder
  containing the downloaded material;
* execute the commands sequentially as they appear in the file;
  the codes were prepared in a way that you do not need to restart Julia
  when working with material from a single chapter, unless it is explicitly
  written in the instructions to restart Julia (some of the codes require this);
* before each code there is a comment allowing you to locate the relevant part
  of the book where it is used; if in the code there is a blank line between
  consecutive code sections this means that in the book these codes are
  separated by the text of the book explaining what the code does

For your convenience I additionally stored data files that we use in this book.
They are respectively:
* movies.dat (for chapter 6, shared on GitHub repository
  https://github.com/sidooms/MovieTweetings under MIT license)
* puzzles.csv.bz2 (for chapter 8, available puzzles at
  https://database.lichess.org/. The data is distributed under
  Creative Commons CC0 license)
* git_web_ml.zip (for chapter 12, available on
  Stanford Large Network Dataset Collection website
  https://snap.stanford.edu/data/github-social.html under GPL-3.0 License)
* owensboro.zip (for chapter 13, available at The Stanford Open Policing Project
  under the Open Data Commons Attribution License)
