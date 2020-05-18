# 1. HTML links  
HTML links are hyperlinks.  
You can click on a link and jump to another document.  
**Note**: A link does not have to be text. It can be an image or any other HTML element.
```
<a href="url">link text</a>
```
- Local Links  
A local link (link to the same web site) is specified with a relative URL (without https://www....).
```
<a href="html_images.asp">HTML Images</a>
```

## The target Attribute
The target attribute specifies where to open the linked document.

The target attribute can have one of the following values:

- **_blank** - Opens the linked document in a new window or tab  
- **_self** - Opens the linked document in the same window/tab as it was clicked (this is default)  
- **_parent** - Opens the linked document in the parent frame  
- **_top** - Opens the linked document in the full body of the window  
- **framename** - Opens the linked document in a named frame
  
