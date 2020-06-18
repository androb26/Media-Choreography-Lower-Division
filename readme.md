# Media Choreography for Lower Division Students

## Introduction
- This repository contains the source code for applications to be used for teaching the course, in directories ordered by curricular units.
- In the future, look in the "Releases" section for compiled applications built from the source.

## Installation
- These are the steps to install for both development and end-user consumption

### End-User Install
- Go to the "Releases" section and download the latest binaries, I plan to break them up by unit to avoid bloated downloads.
- Follow the link to the media folder (https://drive.google.com/drive/folders/1L37Vj6kG1X14L31r_qrwGHiaCBas4vdP?usp=sharing) to grab our collection of test media.
### Development Install
- Checkout the branch for the unit you plan to develop for in Github Desktop
- Follow the link to the media folder (https://drive.google.com/drive/folders/1L37Vj6kG1X14L31r_qrwGHiaCBas4vdP?usp=sharing) for the collection of test media.

## Development
 - Checkout the branch for the unit you intend to add source options to.
 - Place and commit your code to the unit branch.
 - Feedback will be given in terms of functionality and content.
 - Please include instructions and author in the committed Max patches.
 - Once code has been reviewed, and decisions have been made on including which standalones into individual units, we will move source options to the corresponding unit folder in the master branch.
 
 ### Technical Design Considerations
 - At the moment we are evaluating Max patches to be run as Standalone Applications on Macintosh computers (MacOS Mojave and later)
 - Keep in mind the range in hardware configurations and capabilities within the line of Apple™ brand computers. Design your Max patches to work well on the widest possible array of these options. (e.g. If your patch runs at 10fps on a Mac Pro, consider refactoring to lessen the load)

## Building From Source
 To build each unit's applications from source you need access to this list of software
    - Max 8 (8.1.0 or newer)
    - SC Package (Request access from Connor Rawls, cwrawls@asu.edu)
    - All SC dependencies, listed in the readme for SC
    - Any additional dependencies listed in the indivdiual unit folders.

