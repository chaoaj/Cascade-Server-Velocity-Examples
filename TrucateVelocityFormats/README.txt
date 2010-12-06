Truncating Content Velocity Formats
#macro sections should be inserted at the top of the Velocity Format
- $maxWords should be set to the word limit
- $pageContent should be set to the WYSIWYG/text content that should be truncated
- $pageContent and the #truncateHTMLContent/#truncate can be set and utilized for multiple content sections in one format.
- ${truncatedText} should be placed where ever the truncated content should be output in the format.

truncate - maintain HTML structure
Maintains all html tags, truncates content after so many actual words are output, and then makes sure all open html tags are closed.


truncate - remove all HTML
Strips all html tags and truncates content after so many words.