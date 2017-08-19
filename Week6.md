### Week Six Journal Entry

The tutorial task for this week demonstrated the alternatives methods for opening multiple windows from a webpage or program.

The code can be embedded in the main.js file so that it opens when the program starts.  But this method only works well in a browser.

The alternative is to put the code for opening new windows inside a sub JavaScript file so that it invokes the Electron Helper process.  This is called a __Render Process__.  
>"The render process lives outside of the NodeJS main process, but electron links the two together."  (From Week 6 tutorial notes)

This also helps to reduce the amount of reloading that the program is required to do, which speeds up the process.

Jeff advised that the next assignment task will be given to us after the mid semester study break.