# Trestle-table
A script to turn tables in to responsive data tables
## About Responsive tables

This great post on [css-tricks.com](https://css-tricks.com/responsive-data-tables/) shows a method for collapsing tables in to a single column, at mobile breakpoints, and using the CSS content property to display repeating labels of the THEAD content along side those cells.

##The problem

Unfortunately this means that each table needs to have a small chunk of accompanying CSS written along with it. If you have a lot of tables this is problematic.

##What does the Trestle Tables script do?

The Trestle Table script reads the THEAD content and then prints that in to a style tag in the HEAD of a HTML document.

##NOTE
The 'trestle-table' stylesheet attached to the demo is not tied to a specific system or workflow. The styles will render automatically after script generates the class, inline styles and additional content for mobile view. The 'default' stylesheet applies some default styles to make the table look more handsome. It can be discarded or modified without affecting the core behaviour.

##Quick Instructions
You need to have the trestle-table.js file declared in the "head" tag of your page, before the HTML. Next you need to have a "style" tag with the ID of ''jquery-inserted-css''. The script will inject CSS declarations inline into the style tag. Please make sure that your table HTML structure is clean and follows the conventions within the demo sample. Do not have any spaces in your td or th tags. Do not use any paragraph or formatting otherwise on these elements. Recommended that you disable/remove the console.log commands once the code is successfully working on your website. 

