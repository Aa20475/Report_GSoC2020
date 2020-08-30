**Project Name:**  Intuitive Skeleton Tool for Synfig Studio

**My Name:** J Aditya Abhiram ([@Aa20475](https://github.com/reduz))

**Mentors:** [@morevnaproject](https://github.com/morevnaproject), [@rodolforg](https://github.com/rodolforg) and [@ice0](https://github.com/ice0)

**Weekly Reports:** [[GSoC 2020] Skeleton Tool](https://forums.synfig.org/t/gsoc-2020-skeleton-tool/10765)

# Intuitive Skeleton Tool for Synfig Studio

First of all, I want to thank Synfig Studio and my mentors for giving me this opportunity.

This project has been a heck of a rollercoaster ride! So, let's get to it!

## Motivation:

Synfig Studio is a popular "Tweenless" animation system designed to speed up the animation process by using sprites and digital tweening rather than adding to the illustration workload. 

It has a wide variety of features in which Skeleton-based animation is one. It is a very important feature as it makes animating complex 2D structures exponentially easier. The main goal of this project is to **make an intuitive skeleton tool for Synfig Studio.**

## How to test out the project?

You can find the tutorials and documentation for the tool in the links below.

[Tutorial](https://youtu.be/8qawMmSN55o)

[Documentation](https://synfig.readthedocs.io/en/latest/tools/skeleton.html)

**If you are interested to know how we worked on the project... read on!**

## Project Report:

Please find the proposed plan of implementation of the tool [here](https://synfig-docs-dev.readthedocs.io/en/latest/projects/skeleton.html)

### Timeline

#### *Community Bonding Period*
Finalised the implementation timeline. Familiarised with Synfig's codebase by resolving issues. Added a template of skeleton tool.

#### *Coding Period #1 (June 1st,2020 - June 29th,2020)*
The first coding period was kinda slow, as I kept exploring the codebase more. I was able to implement only the basic click to add bone and Click to set Active bone. 

#### *Coding Period #2 (June 29th,2020 - July 27th,2020)*
The most productive part of the project I'd say. As I got used to the codebase, I was able to perfect the tool better. 
  - Highlighted active Bone
  - Finished "Make Parent to Active Bone" feature.
  - Added support for Skeleton Deformation Layer.
 
All the code till this point was in only one [PR](https://github.com/synfig/synfig/pull/1485). This got merged as the Basic Implementation for the Skeleton Tool and any other issues in it were added to a [milestone](https://github.com/synfig/synfig/milestone/10).

#### *Coding Period #3 (July 27th,2020 - August 24th,2020)*
During this period, I worked on fixing minor bugs in the functionalities and some UI enhancements. Fixed some issues in support to Skeleton deformation layer. Updated the tool options for the skeleton tool. Please check out the [milestone](https://github.com/synfig/synfig/milestone/10) to track the exact progress.

#### *Final Work submission Period (August 24th,2020 - August 31,2020)*
Closed some critical issues and started working on Tutorial and Documentation for the tool.

## My Thoughts about this project:
Synfig Studio is an amazing software! I am very thankful to my mentors for being patient with me and helping out with even the simplest tasks. The lack of good documentation made it a difficult start. Eventhough, I got overwhelmed by the huge codebase initially, once I got used to it, I just enjoyed every moment working with it! I will keep on contributing to Synfig Studio! 

## What's left?
- The tool, as it is now, can be used to make skeletons easily.
- I think it'll be nice to add a capability to bone linking to the tool.




