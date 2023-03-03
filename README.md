# jQuery Snippets

## Features

jQuery snippets for vscode

## Requirement
- jQuery 1.7.0+

Snippets for the most common jQuery features. Works with .js files.

|#| Trigger | Description |
|-|---------|-------------|
|1|`jq:after`|Insert content, specified by the parameter, after each element in the set of matched elements.|
|2|`jq:ajax`|Perform an asynchronous HTTP (Ajax) request.|
|3|`jq:append`|Insert content, specified by the parameter, to the end of each element in the set of matched elements.|
|4|`jq:appendto`|Insert every element in the set of matched elements to the end of the target.|
|5|`jq:attr[get]`|Get the value of an attribute for the first element in the set of matched elements.|
|6|`jq:attr[set]`|Set one or more attributes for the set of matched elements.|
|7|`jq:attr[function]`|Get the value of an attribute for the first element in the set of matched elements.|
|8|`jq:removeattr`|Remove an attribute from each element in the set of matched elements.|
|9|`jq:before`|Insert content, specified by the parameter, before each element in the set of matched elements.|
|10|`jq:bind`|Attach a handler to an event for the elements.|
|11|`jq:bind[data]`|Attach a handler to an event for the elements.|
|12|`jq:blur`|Bind an event handler to the \"blur\" JavaScript event, or trigger that event on an element.|
|13|`jq:change`|Bind an event handler to the \"change\" JavaScript event, or trigger that event on an element.|
|14|`jq:addclass`|Adds the specified class(es) to each element in the set of matched elements.|
|15|`jq:removeclass`|Remove a single class or multiple classes from each element in the set of matched elements.|
|16|`jq:toggleclass`|Add or remove one or more classes from each element in the set of matched elements, depending on either the class's presence or the value of the state argument.|
|17|`jq:click`|Bind an event handler to the \"click\" JavaScript event, or trigger that event on an element.|
|18|`jq:click[function]`|Bind an event handler to the \"click\" JavaScript event, or trigger that event on an element.|
|19|`jq:clone`|Create a deep copy of the set of matched elements.|
|20|`jq:contextmenu`|Bind an event handler to the \"contextmenu\" JavaScript event, or trigger that event on an element.|
|21|`jq:css[get]`|Get the computed style properties for the first element in the set of matched elements.|
|22|`jq:css[set]`|Set one or more CSS properties for the set of matched elements.|
|23|`jq:data[get]`|Store arbitrary data associated with the matched elements.|
|24|`jq:data[set]`|Store arbitrary data associated with the matched elements.|
|25|`jq:removedata`|Remove a previously-stored piece of data.|
|26|`jq:dblclick`|Bind an event handler to the \"dblclick\" JavaScript event, or trigger that event on an element.|
|27|`jq:die`|Remove event handlers previously attached using .live() from the elements.|
|28|`jq:ready`|Specify a function to execute when the DOM is fully loaded.|
|29|`jq:document`|Specify a function to execute when the DOM is fully loaded.|
|30|`jq:each`|Iterate over a jQuery object, executing a function for each matched element.|
|31|`jq:each[element]`|Iterate over a jQuery object, executing a function for each matched element.|
|32|`jq:empty`|Remove all child nodes of the set of matched elements from the DOM.|
|33|`jq:fadein`|Display the matched elements by fading them to opaque.|
|34|`jq:fadein[function]`|Display the matched elements by fading them to opaque.|
|35|`jq:fadeout`|Hide the matched elements by fading them to transparent.|
|36|`jq:fadeout[function]`|Hide the matched elements by fading them to transparent.|
|37|`jq:fadeto`|Adjust the opacity of the matched elements.|
|38|`jq:fadeto[function]`|Adjust the opacity of the matched elements.|
|39|`jq:find`|Get the descendants of each element in the current set of matched elements, filtered by a selector, jQuery object, or element.|
|40|`jq:focus`|Bind an event handler to the \"focus\" JavaScript event, or trigger that event on an element.|
|41|`jq:focusin`|Bind an event handler to the \"focusin\" event.|
|42|`jq:focusout`|Bind an event handler to the \"focusout\" JavaScript event.|
|43|`jq:get`|Load data from the server using a HTTP GET request.|
|44|`jq:getjson`|Load JSON-encoded data from the server using a GET HTTP request.|
|45|`jq:getscript`|Load a JavaScript file from the server using a GET HTTP request, then execute it.|
|46|`jq:hasclass`|Determine whether any of the matched elements are assigned the given class.|
|47|`jq:height[get]`|Get the current computed height for the first element in the set of matched elements.|
|48|`jq:height[set]`|Set the CSS height of every matched element.|
|49|`jq:hide`|Hide the matched elements.|
|50|`jq:hide[function]`|Hide the matched elements.|
|51|`jq:hover`|Bind two handlers to the matched elements, to be executed when the mouse pointer enters and leaves the elements.|
|52|`jq:html[get]`|Get the HTML contents of the first element in the set of matched elements.|
|53|`jq:html[set]`|Set the HTML contents of each element in the set of matched elements.|
|54|`jq:innerheight`|Get the current computed height for the first element in the set of matched elements, including padding but not border.|
|55|`jq:innerwidth`|Get the current computed inner width for the first element in the set of matched elements, including padding but not border.|
|56|`jq:insertafter`|Insert every element in the set of matched elements after the target.|
|57|`jq:insertbefore`|Insert every element in the set of matched elements before the target.|
|58|`jq:keydown`|Bind an event handler to the \"keydown\" JavaScript event, or trigger that event on an element.|
|59|`jq:keypress`|Bind an event handler to the \"keypress\" JavaScript event, or trigger that event on an element.|
|60|`jq:keyup`|Bind an event handler to the \"keyup\" JavaScript event, or trigger that event on an element.|
|61|`jq:load`|Bind an event handler to the \"load\" JavaScript event.|
|62|`jq:load[function]`|Bind an event handler to the \"load\" JavaScript event.|
|63|`jq:map`|Pass each element in the current matched set through a function, producing a new jQuery object containing the return values.|
|64|`jq:mousedown`|Bind an event handler to the \"mousedown\" JavaScript event, or trigger that event on an element.|
|65|`jq:mouseenter`|Bind an event handler to be fired when the mouse enters an element, or trigger that handler on an element.|
|66|`jq:mouseleave`|Bind an event handler to be fired when the mouse leaves an element, or trigger that handler on an element.|
|67|`jq:mousemove`|Bind an event handler to the \"mousemove\" JavaScript event, or trigger that event on an element.|
|68|`jq:mouseout`|Bind an event handler to the \"mouseout\" JavaScript event, or trigger that event on an element.|
|69|`jq:mouseover`|Bind an event handler to the \"mouseover\" JavaScript event, or trigger that event on an element.|
|70|`jq:mouseup`|Bind an event handler to the \"mouseup\" JavaScript event, or trigger that event on an element.|
|71|`jq:offset`|Get the current coordinates of the first element in the set of matched elements, relative to the document.|
|72|`jq:offsetparent`|Get the closest ancestor element that is positioned.|
|73|`jq:on`|Attach an event handler function for one or more events to the selected elements.|
|74|`jq:one`|Attach a handler to an event for the elements. The handler is executed at most once per element per event type.|
|75|`jq:one[data]`|Attach a handler to an event for the elements. The handler is executed at most once per element per event type.|
|76|`jq:outterheight`|Get the current computed outer height (including padding, border, and optionally margin) for the first element in the set of matched elements.|
|77|`jq:outterwidth`|Get the current computed outer width (including padding, border, and optionally margin) for the first element in the set of matched elements.|
|78|`jq:position`|Get the current coordinates of the first element in the set of matched elements, relative to the offset parent.|
|79|`jq:post`|Send data to the server using a HTTP POST request.|
|80|`jq:prepend`|Insert content, specified by the parameter, to the beginning of each element in the set of matched elements.|
|81|`jq:prependto`|Insert every element in the set of matched elements to the beginning of the target.|
|82|`jq:remove`|Remove the set of matched elements from the DOM.|
|83|`jq:replaceall`|Replace each target element with the set of matched elements.|
|84|`jq:replacewith`|Replace each element in the set of matched elements with the provided new content and return the set of elements that was removed.|
|85|`jq:resize`|Bind an event handler to the \"resize\" JavaScript event, or trigger that event on an element.|
|86|`jq:scroll`|Bind an event handler to the \"scroll\" JavaScript event, or trigger that event on an element.|
|87|`jq:scrollleft[get]`|Get the current horizontal position of the scroll bar for the first element in the set of matched elements.|
|88|`jq:scrollleft[set]`|Set the current horizontal position of the scroll bar for each of the set of matched elements.|
|89|`jq:scrolltop[get]`|Get the current vertical position of the scroll bar for the first element in the set of matched elements or set the vertical position of the scroll bar for every matched element.|
|90|`jq:scrolltop[set]`|Set the current vertical position of the scroll bar for each of the set of matched elements.|
|91|`jq:select`|Bind an event handler to the \"select\" JavaScript event, or trigger that event on an element.|
|92|`jq:select[function]`||Bind an event handler to the \"select\" JavaScript event, or trigger that event on an element.
|93|`jq:show`|Display the matched elements.|
|94|`jq:show[function]`|Display the matched elements.|
|95|`jq:slidedown`|Display the matched elements with a sliding motion.|
|96|`jq:slidedown[function]`|Display the matched elements with a sliding motion.|
|97|`jq:slidetoggle`|Display or hide the matched elements with a sliding motion.|
|98|`jq:slideup`|Hide the matched elements with a sliding motion.|
|99|`jq:slideup[function]`|Hide the matched elements with a sliding motion.|
|100|`jq:submit`|Bind an event handler to the \"submit\" JavaScript event, or trigger that event on an element.|
|101|`jq:submit[function]`|Bind an event handler to the \"submit\" JavaScript event, or trigger that event on an element.|
|102|`jq:text[get]`|Get the combined text contents of each element in the set of matched elements, including their descendants.|
|103|`jq:text[set]`|Set the content of each element in the set of matched elements to the specified text.|
|104|`jq:toggle`|Bind two or more handlers to the matched elements, to be executed on alternate clicks.|
|105|`jq:toggle[function]`|Bind two or more handlers to the matched elements, to be executed on alternate clicks.|
|106|`jq:trigger`|Execute all handlers and behaviors attached to the matched elements for the given event type.|
|107|`jq:trigger[data]`|Execute all handlers and behaviors attached to the matched elements for the given event type.|
|108|`jq:trigger[function]`|Execute all handlers and behaviors attached to the matched elements for the given event type.|
|109|`jq:triggerhandler`|Execute all handlers attached to an element for an event.|
|110|`jq:triggerhandler[data]`|Execute all handlers attached to an element for an event.|
|111|`jq:unbind`|Remove a previously-attached event handler from the elements.|
|112|`jq:unbind[function]`|Remove a previously-attached event handler from the elements.|
|113|`jq:unload`|Bind an event handler to the \"unload\" JavaScript event.|
|114|`jq:val[get]`|Get the current value of the first element in the set of matched elements.|
|115|`jq:val[set]`|Set the value of each element in the set of matched elements.|
|116|`jq:width[get]`|Get the current computed width for the first element in the set of matched elements.|
|117|`jq:width[set]`|Set the CSS width of each element in the set of matched elements.|
|118|`jq:wrap`|Wrap an HTML structure around each element in the set of matched elements.|
|119|`jq:wrapall`|Wrap an HTML structure around all elements in the set of matched elements.|
|120|`jq:wrapinner`|Wrap an HTML structure around the content of each element in the set of matched elements.|

## Release Notes

### 1.0.0

- Initial release

