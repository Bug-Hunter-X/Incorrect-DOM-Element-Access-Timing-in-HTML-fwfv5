# Incorrect DOM Element Access Timing in HTML

This repository demonstrates a common but subtle bug in HTML and JavaScript: attempting to access a DOM element before it has been fully parsed and added to the document.  The issue arises when JavaScript tries to interact with an element that doesn't yet exist in the browser's DOM.