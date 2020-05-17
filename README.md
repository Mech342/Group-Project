## Ball and Plate 

![Model_Image](https://user-images.githubusercontent.com/65363589/82133838-4ae2d880-97a5-11ea-9ba0-2c7557ba91b6.JPG)

# Group Members

## Rebecca Allan, Dana Fisk, Carl Quicksall, Samuel Wright, Alyssa Zuniga





# Project Summary 
The group chose the ball and plate control algorithm project unanimously, as all members were interested in creating this control algorithm. 
The challenge of this project is to demonstrate the ability to balance a ball on a moving plate using a PID-based controller that can sense the movement of the ball and plate while using an algorithm to balance and eventually stabilize the ball in a desired position on the plate. 
This will be accomplished using two rotary servo base units in conjunction with two degrees of freedom. A camera will be implemented to sense and record the location of the ball and pass that information to the controller, giving it the data it needs to compensate and adjust the plate.

The four main platforms used to build this system were: MATLAB, Simulink, CoppeliaSim, and Quarc.  MATLAB is used as the primary computation engine. 
CoppeliaSim is our simulation platform that allows us to build a virtual model of our robot. Simulink acts as the go between MATLAB and CoppeliaSim and Quark is a watchdog that provides additional features. Together these four systems make up our full PID system.

In regards to our requirements, we were able to derive a transfer function, to properly model the physical system. We were able to generate a simulated model of the physical system as well as create a control system prototype that is ready to be implemented in Simulink. We were not however successful in our attempts to integrate the transfer function with the virtual system.




# Project Files

[Design Report](https://github.com/Mech342/Group-Project/files/4640779/Design.Report.pdf)
- Presentation
[Simulation File](https://github.com/Mech342/Group-Project/files/4640815/Ball.and.Plate.pptx)
- Software Files - these woudl be better if they were ours but ill work on it.
[Courseware Resources (given) ](https://github.com/Mech342/Group-Project/files/4640829/Courseware.Resources.8.zip)
- V-REP File
- Code Source

[Code Source - Software ](https://github.com/Mech342/Group-Project/files/4640839/Software-20200517T191224Z-001.zip)

[Code Source - Documentaton ](https://github.com/Mech342/Group-Project/files/4640841/Documentation-20200517T191250Z-001.zip)

[Software-20200517T191412Z-001.zip](https://github.com/Mech342/Group-Project/files/4640847/Software-20200517T191412Z-001.zip)



You can use the [editor on GitHub](https://github.com/Mech342/Group-Project-/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text



![](https://media.giphy.com/media/mR3FqAStFhyiQ/giphy.gif)
![cat](https://user-images.githubusercontent.com/65363589/81987504-9d2dc900-95ee-11ea-8eca-e0c12f1b5fa4.jpg)


For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Mech342/Group-Project-/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
