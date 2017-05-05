# D2 - Developer Documentation
Quick access to popular libraries, frameworks & tools online developer documentation.

With all these great frameworks & libraries out there, it's hard to master each one of them.
**D2** (Developer Documentation) provides links to online documentation of the most popular frameworks, libraries and other development tools, so you’ll able to get some answers quickly.  

D2 is available both as Chrome extension and Alfred Workflow.

## Alfred Workflow
D2 workflow for Alfred can be downloaded from [Packal](http://www.packal.org/workflow/d2-developer-documentation).

## Chrome Extension

### Installation
1. Open [D2 page on Chrome Web Store](https://chrome.google.com/webstore/detail/d2-developer-documentatio/pcndaioeajanljljbjglanbmnmhgdjln)
2. Click on the blue "Add to Chrome" button
3. Confirm installation by clicking on the "Add extension" button

### How To Use
1. Click on the extension's logo to open the links list.  
Alternatively, you can set a keyboard shortcut on Chrome Extensions page (chrome://extensions/ >> Keyboard shortcuts)
2. Open a link:
    - Type a tool's name and press enter, or:
    - Click on the search icon, type a tool's name and click on its link, or:  
    - Scroll down with your mouse and click on any link

## Submit a New Link
1. Open [D2 repository](https://github.com/nire0510/d2) on Github
2. Make sure the link is not already in the file
3. [Edit `data.json` file](https://github.com/nire0510/d2/edit/master/data.json)
4. Add your link object to the bottom of the array:
```json
{
  "name": "Tool's name as appear on its website",
  "description": "Tool's description as appear on its website, up to 100 characters",
  "tags": ["lowered", "case", "tags"],
  "link": "direct link to documentation / api page, e.g. https://emberjs.com/api/",
  "timestamp": "current date as YYYY-MM-DD, e.g. 2017-01-01",
  "credit": "your_username@some_website, e.g. nire0510@github"
}
```
5. Submit your PR
