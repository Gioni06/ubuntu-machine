# Ubuntu Machine
A collection of useful tools, software and plugins.   

## Table of contents

<!-- MarkdownTOC depth=0 -->

- [Software](#software)
	- [Editors and IDE](#editors-and-ide)
	- [Tools](#tools)
	- [Browser](#browser)
	- [Package Management](#package-management)
	- [Communication](#communication)
	- [Misc](#misc)
- [Fonts](#fonts)
- [Blogs](#blogs)

<!-- /MarkdownTOC -->


<a name="software"></a>
## Software

<a name="editors-and-ide"></a>
### Editors and IDE

1. PHPStrom
2. Sublime Text
    - Markdown Highlighter
    - Markdown Preview

<a name="tools"></a>
### Tools

1. Meld diff merge
2. Giggle
3. Terminator
	-	Terminator + Oh My ZSH with Agnoster Theme [https://gist.github.com/renshuki/3cf3de6e7f00fa7e744a](https://gist.github.com/renshuki/3cf3de6e7f00fa7e744a)
4. Password-Gorilla
5. KeePassX
5. Dropbox
6. Unity Tweak
7. MySql Workbench

<a name="browser"></a>
### Browser

1. Chromium
2. Firefox

<a name="package-management"></a>
### Package Management

1. Synaptic Package Manager
    - Xapian `sudo apt-get xapian` + `sudo update-apt-xapian-index -vf`
2. GDebi Package Manager ( Ubuntu 16.04 has a bug with some some `.deb` Packages )
 
<a name="communication"></a>
### Communication

1. Thunderbird
    - Lightning Calendar Plugin
    - Exchange Plugin [https://github.com/Ericsson/exchangecalendar/](https://github.com/Ericsson/exchangecalendar/)
    - Provider For Google Calendar *Note - Exchange Plugin needs to be disabled in order to setup Google Calendars (possible bug).*
2. Slack
3. Skype

<a name="misc"></a>
### Misc

1. Move Unity Dock
	- `gsettings set com.canonical.Unity.Launcher launcher-position Left`
2. Enable HDMI Sound output
	- `sudo adduser $USER audio`	
3. List 5 most used commands
	- `history | awk '{print $2};' | sort | uniq -c | sort -rn | head -5`

<a name="fonts"></a>
## Fonts

1. [http://sourcefoundry.org/hack/](http://sourcefoundry.org/hack/) - Coding Font

<a name="blogs"></a>
## Blogs

1. [http://tuxdiary.com/](http://tuxdiary.com/)
