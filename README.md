
## 關於計畫

美國人希望能透過數位管道，像是網站、電子郵件或行動應用來和政府互動。透過建立更好的數位服務，來滿足使用這些服務的民眾需求，可以更有效的傳達政府政策和計畫。

其中一個改善數位服務傳遞，讓它更聰明的方式是以正確手續和實踐，來驅使產出的結果具信賴度，並且讓參與的人及公司都能全力以赴。數位遊戲書以及數位聯邦採購法手冊便是紀錄這些正確的手續與實踐：

- [**數位遊戲書**](http://playbook.taipei.io) 將一系列的**遊戲**從公私兩方的成功實踐的最好方法列出，如果照著進行，將能協助政府建立更有效的數位服務。這些遊戲概要列出一個途徑，讓交付服務這件事對我們來說有更大彈性、遞迴地進行，以及更重要的—關注服務使用者的需求。
- [**科技聯邦採購規範手冊**](http://playbook.taipei.io/tecfar)（譯註：尚未翻譯）則是凸顯聯邦採購規範(FAR)中的彈性，來幫助機關採用手冊中的**遊戲**，並在採購支持下達到目的—尤其關注在如何讓承包商能支援遞迴、消費者導向的軟體開發程序，就如同私有企業的例行公事一樣。

## About This Project

The American people expect to interact with government through digital channels such as websites, email, and mobile applications. By building better digital services that meet the needs of the people that use our services, we can make the delivery of our policy and programs more effective.

One way to advance smarter digital service delivery is by putting the right processes and practices in place to drive outcomes and accountability and allow people and companies to do their best work.  The Digital Services Playbook and the TechFAR Handbook document these best practices and processes: 

- [**The Digital Services Playbook**](http://playbook.cio.gov "Link to the Digital Services Playbook") identifies a series of “plays” drawn from successful best practices from the private sector and government that, if followed together, will help government build effective digital services.  The plays outline an approach to delivering services that increases our ability to be flexible, iterative and, most importantly, to focus on the needs of the people that use our services.
- [**The TechFAR Handbook**](http://playbook.cio.gov/techfar "Link to the TechFAR Handbook") highlights the flexibilities in the Federal Acquisition Regulation (FAR) that can help agencies implement “plays” from the Playbook that would be accomplished with acquisition support – with a particular focus on how to use contractors to support an iterative, customer-driven software development process, as is routinely done in the private sector.

## We Want Your Feedback
We encourage your feedback and suggestions on these documents. Content and feature suggestions and discussions are welcome via [GitHub Issues](https://github.com/WhiteHouse/playbook/issues). You may also propose changes to the content directly by submitting a [pull request](https://help.github.com/articles/creating-a-pull-request "More Information on Submitting Pull Requests").

You don't need to install any software to suggest a change. To propose a change from your browser, [select a play in the `_plays` folder](https://github.com/WhiteHouse/playbook/tree/gh-pages/_plays "Link to the Plays Markdown files"), or open the [TechFAR file](https://github.com/WhiteHouse/playbook/blob/gh-pages/_includes/techfar-online.md "Link to the TechFAR Markdown File"). You can use Github's in-browser editor to edit files and submit a "pull request" for your changes to be merged into the document. 

If you would like to see and discuss the changes that other people have proposed, [visit the "Pull Requests" section](https://github.com/WhiteHouse/playbook/pulls "Link to the Pull Requests Section of Github") and [browse the issues](https://github.com/WhiteHouse/playbook/issues "Link to the Issues Section of Github").

Feedback collected before September 1, 2014 will be considered for inclusion in the next release of the Digital Services Playbook and the TechFAR Handbook.

## Technical Details

The Playbook and the TechFAR Handbook are compiled from [Markdown](https://help.github.com/articles/github-flavored-markdown "Link to More Information About Markdown") files using [Jekyll](https://github.com/jekyll/jekyll "Link to More Information about Jekyll"). To propose a specific change, you can submit a [pull request](https://help.github.com/articles/creating-a-pull-request "More Information on Submitting Pull Requests") with your change to one of these source Markdown files. The Plays from the Playbook are [available in the `_plays` folder](https://github.com/WhiteHouse/playbook/tree/gh-pages/_plays "Link to the Plays Markdown files"), while the [TechFAR is contained in this markdown file](https://github.com/WhiteHouse/playbook/blob/gh-pages/_includes/techfar-online.md "Link to the TechFAR Markdown File").

You can also use Github's in-browser editing feature to make an edit to one of these Markdown files and submit your change for consideration without needing to install any additional software.

### Running the Site Locally

To run the site locally on your own computer (most helpful for previewing your own changes), you will need to install Jekyll and other dependencies:

If you don't already have Ruby and Bundler installed, follow [the first two steps in these Jekyll installation instructions](https://help.github.com/articles/using-jekyll-with-pages#installing-jekyll "Installation instructions for Jekyll").

Next, [fork this repository](http://help.github.com/fork-a-repo/ "Instructions for Forking Your Repository") and clone it on your computer.

Navigate to the folder on your computer, and run the command `$ bundle install` at the command line prompt.

To run the site locally, run `jekyll serve --watch`, then visit `http://localhost:4000/` in your browser to preview the site.

### Editing the Stylesheets

This project uses [Sass](http://sass-lang.com/ "Link to Learn More About Sass") for managing its style sheets. If you would like to make changes to the site's styles, you should edit the `assets/sass/styles.css.scss` file. 
**Do not** make changes to the `styles.css` file directly, as this file is auto-generated from the `styles.css.scss` file.

To compile changes in the `styles.css.scss` Sass file into a new `styles.css` file, you can run: `$ sass --watch assets/sass/styles.css.scss:assets/css/styles.css`. This command will watch for any changes you make to the Sass file and automatically update the CSS file, making it easy to check your work when you are running the site locally (see above).

## License
As a work of the United States Government, this project is in the public domain within the United States.

Additionally, we waive copyright and related rights in the work worldwide through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
