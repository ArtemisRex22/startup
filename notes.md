# Git experience
 I really had a difficult time with this at first, but after a few hours of dedicated practice, I feel that I am in a very good position to learn how getting good at using this will increase my productivity and make me a better addition to society.
# 1.1
What they look for:
    Capable
    Creative
    Curious
    Collaborative
    Christlike

Learn:
    Command Console 
    Git & GitHub
    Web Servers
    HTTPS
    Domain names, DNS
    Web Certificates 
    Web Design
    Security
    HTML
    CSS
    JavaScript
    Web Services
    Database storage
    User Authentication
    Websockets
    React
# 1.2
Tim Berners_Lee effectively invented the internet, he is the father of HTP, HTML, and URL
Hakon Wium Lie invented CSS
Brendan Eich invented JavaScript
# 1.3
HTML - Structure
CSS - Style
JavaScript - Interaction
Service - Web Service endpoints (Save scores, get weather)
Database/login - Persisted app and auth data 
WebSocket - Data pushed from server, chat, real time peer interaction
React - Web framework
# 1.4
Operating Systems
    Linux
    Mac
    Windows
    WSL
Console commands:
    echo - Output the parameters of the command
    cd - Change Directory
    mkdir - Make Directory
    rmdir - Remove Directory
    rm - Remove file(s)
    mv - Move file(s)
    cp - Copy files
    ls - List files
    curl - COmmand line client URL browser
    grep - Regular expression search
    find - Find files
    top - View running processes
    df - View disk statistics
    cat - Output file
    less - Interactive file outpus
    wc - Count words
    ps - View processes
    kill - Kill a process
    sudo - Execute as admin
    ssh - Remote shell
    scp - Securely copy files to a remote computer
    history - SHow history of commands
    ping - Test connection
    tracert - Trace network
    dig - DNS information
    man - Look in the manual
Control keys:
    CTRL-C - Cancel command
    CTRL-R - Recall command
    CTRL-Z - Background command
VIM = Visual instrument improved
# 1.5
Linus Torvalds invented Linux and Git
Version repository for a directory
    Allows for repository collaboration
It allows you to track versions of files in a directory, and it allowsyou to to clone all of those versions to a different location.
# 1.6 Github

# 2.1 Stack, EC2 & Route 53
Technology Stack:
    React
    Caddy 2
    Node
    MongoDB
EC2 refers to the server
Route53 refers to the domain name
# 2.3 Caddy, HTTPS, TLS, certs
caddy
HTTPS & TLS
Web Certificates
    Security Credential
# 3.1 HTML
The Structure
    <html lang="en">
    </html>
In this case the open tag is the whole first line
The attribute is lang
The attribute value is "en"
and the second line is the close tag
Link References:
    Absolute
    Relative (They are relative if the href has a / after it (a href="profile.png" /))
Elements and their meanings
    html - The page containe
    head - Header information
    title - Title of the page
    body - The entire content body of the page
    header - Header content
    main - Main content of the page
    footer - Footer of the main content
    section - A section of main content
    div - A block division of content
    spa - An inline span of content
    h,1-9 - Text heading. From h1, the highest level, down to h9, the lowest level
    p - A paragraph of text
    table - Table
    ol,ul - Ordered or unordered list
    a - Anchor text to a hyperlink
    img - Graphical image reference
# 3.2
    Simon Startup, hands on info about HTML for startup
# 3.3 CSS
    Syntax
    p {
        color: green;
    }
    p is the selector
    color is the property
    : is the declaration
    green is the value
    The whole thing is the rule
Selectors and their meanings 
    element - All elements of a specific name (p or div)
    ID - The element with the given ID (#root)
    class - All elements with the given class (.highlight)
    element class - any elements with the specific name and class (p.highlight)
    List - Any of the given selectors (body,section)
    Descendant - A list of descendants (body section)
    child - A list of direct children (section > p)
    Pseudo - state based (p:hover) (The mouse is hevering over a p element)
Declarations:
    Properties:
        background-color - color (fills the background color)
        border - color and width style (Sets the border using shorthand where any or all of the values may be provided)
        Color - color (Sets the text color)
        display - type (Defines how to display the element and its children)
        font - Family, size, and style (Defines the text font using shorthand)
        margin - unit (Sets the margin spacing)
        padding - unit (Sets the padding spacing)
    Units:
        px - the number of pixels
        pt - The number of points (1/72 of an inch)
        % - A percentage of the parent element
        em - A multiplier of the width of the letter m in the parent's font
        rem - A multiplier of the width of the letter m in the root's font
        vw - A percentage of the viewport's width
        vh - A percentage of the viewport's height
        vmin - A percentage of the viewport's smaller dimension
        vmax - A percentage of the viewport's larger dimension
        Where a viewport is the display screen of the thing you are accessing the website on
# 3.4
Fonts, animation, practice
@font-face {
    font-family: 'samplefont';
    src: url('sampleurl')  
}

p {
    font-family: samplefont;
}
or @import
url(fonturl)
Unicode and UTF-8
    "<meta charset="UTF-8">"
    And then you can do special characters like emojis or non-alpha-numeric characters
Animation:
    p {
        text-align: sampletextalignment;
        font-size: samplesizevh;

        animation-name: demo;
        animation-duration: 3s;
    }
    @keyframes demo {
        from {
            font-size: declareit;
        }
        95% {
            font-size: declareit;
        }
        to{
            font-size: declareit;
        }
    }
# 3.5
Responsive, grid, flex
Syntax:
    <meta name="viewport" />
    float:right
    display:grid
    display:flex
    @media
Viewport:
    <meta name="viewport"
          conten="width=device-width, initial-scale=1"/>
Float:
    aside {
        float: right;
        padding: 3em;
        margin: .5em;
        border: black solid thin;
    }
Display:
    none
    block
    inline
    flex
    grid
Grid:
    <div class="container">
        ... many other div objects to represent individual cells of a grid
    .container {
        display: grid;
        grid-template-columns
            repeat(auto-fill, minmax(20))
    } 
Flex:
    Flex influences how much different parts of a page can be changed around to different sizes 
    body {
        display: flex;
        flex-direction: column
        margin: 0;
        height: 100
    }
Media Queries:
    @media (orientation: portrait) {
        div {
            transform: rotate(certaindegrees)
        }
    }
    
    @media (orientation: portrait) {
        body {
            flex-direction: column;
        }
    }

    @media ((orientation: portrait)
    and (max-height: 500px)) {
        aside {
            display: none;
        }
    }
    You can also do it for header and footer, the main purpose of this is to flex media on a page, like images and the like.

# 3.6
    Hands-on debugging stuff, not any information likely to be on a test

# 4.1 JavaScript
    Inspired by Scheme
    Interpreted
    Dynamically typed
    Timeline:
        1995 JS invented
        1997 JS becomes EMCAScript
        2009 ES5: strict JSON, array iteration
        2015-xx - ES6: let, default params, async, rest/spread, destructure, module, class, template literals
    Playgrounds (Places to use JS):
        Browser debugging consoler
        CodePen
        VSCode (LiveServer)
        Node.js
    index.js
        function sayHello() {
            console.log(log('hello));
        }
    In HTML you would create a script element with the source being a JS file (<script src="index.js"></script>)
    And add script attributes

    function testAll(input, tester) {
        const result = // Your code here
        return result
    }

    const result = testAll(/* Your parameters here */);

    console.log(result);

    JS example^
# 4.4
Document object model (DOM)
Event handlers
    Event categories:
        Clipboard - Cu, copied, pasted
        Focus - An element gets focus
        Keyboard - Keys are pressed
        Mouse - Click
        Text selection - When text is selected
Common JS Modules:
    Function hello() { console.log('hello'); }
    module.exports = { hello };

    const greet = require('./greet');
    greet.hello();

    alert.js
    export function alertDisplay(msg) {
        alert(msg);
    }

    main.js
    import { alertDisplay } from './alert.js';
    alertDisplay('called from main.js');

    index.html

    <html>
      <body>
        <script type="module">
          import ( alertDisplay ) from '.alert.js';
          window.btnClick = alertDisplay;
        </script>
        <button onclick="btnClick('called from index.html')">
          Press me
        </button>
      </body>
    </html>

# 4.5
Promises, async/await
Browser rendering is single threaded
Everthing must be asynchronous
Promise
    pending - Currently running asychronously
    fulfilled - Completed successfully
    rejected - Failed to complete
    Syntax
        new Promise((resolve, reject) => resolve(true))
        resolve is the callback
        resolve(true) is the return
async/await
    Syntax:
        try {
            const result = await promisesample;
            console.log("Toss result ${result}');
        }   catch (err) {
            console.error('Error: ${err}');
        }   finally {
            console.log('Toss completed);
        }
    Rule for using await
        top level module function or called from an async function
    Remember that async will auto-generate a promise if not explicitly returned