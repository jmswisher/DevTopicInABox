# Contributing to DevTopicInABox
We welcome contributions to this project. In keeping with the [Mozilla Participation Guidelines](https://www.mozilla.org/en-US/about/governance/policies/participation/), we welcome contributions from anyone who participates constructively.

## Ways to contribute
The main ways to contribute to this project are:
* Improving an existing topic box 
* Submiting issues about the project
* Translating a topic box into another language
* Contributing a new topic box

## Improving an existing box
There are many ways to improve existing topic boxes, such as:
* Adding optional elements
* Updating code to match API changes
* Other enhancements based on experience with using the box

Please submit a pull request with your changes. 

## Submitting issues
Use the issue-tracker built in to Github to submit issues. Please feel free to report bugs or suggest topics, even if you are not able to resolve the issue yourself. We'd like to know about problems with this project and areas of interest to its users. Use the labels such as "bug", "enhancement", "question" and "help wanted" to indicate the type of issue.

## Translating a topic into another language
Create an issue for the translation, if one doesn't exist already. Assign the issue to yourself.

Fork the project, and create a new subdirectory for the topic you want to translate, under the appropriate language directory. (If you want to translate to a new language, create a directory for that as well, based on the language code.) Copy the resources from the original topic box into the new directory, and translate them. 

**Note:** Weigh the pros and cons of translating text inside the example code for the topic. On the plus side, translating comments, output text, and variable names makes the code more accessible for speakers of your target language. On the minus side, "forking" code from one directory to another within a project is not supported by git, so you will have to manage merging future changes in the original code yourself. The simplest approach is to reference the code (untranslated) in its original location.

Please submit a pull request with your changes.

## Creating a new topic box

You should relate any work you do for creating a new topic box to an issue in the project issue-tracker. You can pick a topic on our wishlist, or you can submit an issue, and then work on it. Be sure to assign the issue to yourself.

It's a good idea to open a pull request early in your work, so you can get feedback along the way.

### Minimum requirements
A topic box *must* contain at least the following elements:
* A *code project* that demonstrates the topic. This is obviously a must for API topics. Even if the topic is about a developer tool, provide a sample file or project that people can use to play with the relevant features of the tool (for example, for a CSS tool, provide a CSS file and an HTML file that uses it). If you don't have a code project, you need to make a persuasive argument why code is not relevant for the topic.
  * Follow [best practices for example code](http://www.developer-evangelism.com/code.php) to make your code project self-contained and practical.
  * Document *any* external dependencies (even jQuery), to ensure that others can find everything they would need to run your code.
  * All media (graphics, video, audio) files included with your project must be openly licensed to enable others to copy them. Include license references and attributions in your README.md file.
* A *script for demoing* the topic. This is a list of actions a presenter takes to demonstrate the API, tool, etc. 
* *Presentation notes* outlining the main points that a presenter should make about the topic. 

### Optional elements
* Presentation slides, preferably in an HTML5 slide format. As with code, follow [best practices for slides](http://www.developer-evangelism.com/slides.php) rather than just putting your presentation notes into bullet points.
* Video about the topic. This can be a screencast of a demo, an interview with an expert on the topic, or whatever makes sense for the topic. If the video shows a demo, use the same script as is in the topic box, so that viewers can follow along locally.
* Suggested activities for participants. Suggest something that people can try to do with the code that goes beyond what is in the demo script. If you give a challenge, be sure to include at least one possible solution.
* Suggested discussion questions, for participants who are learning about the topic together to talk about. These should be open-ended issues that there may be a variety of opinions about.
* Links to other resources. If there are articles on [Hacks](http://hacks.mozilla.org), [MDN](https://developer.mozilla.org), or elsewhere on the Web, be sure to reference them in the README.md for the topic box.
