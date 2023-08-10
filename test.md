This is a test of the markdown editor. For some reason, sometimes, the cursor seems to jump to position 1,1 in the file while I'm typing. I bet it's going to be impossible to reproduce it now…

But we must be patient, for the bug will surely reveal itself in the fullness of time. I have noticed it most in longer documents, so perhaps some Lorem Ipsum is called for.

### I wonder

- Does adding things at the top of the document make a difference?
- No, it doesn't seem to, this feels snappier than in my other repo
- What on earth is going on?
- What size of document is required to make this break?
  - How about indents?
  ```
  How about code blocks
  ```
  - How about other stuff: **bold**
  - What about [links to things](google.com)
  - Nothing seems to phase this bloody thing.

## The Lipsum
Happily, [lipsum.com] is still around:

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer mollis auctor nibh, quis egestas arcu finibus vel. Maecenas congue nisl eget orci porta, sit amet tempus augue faucibus. Mauris lobortis odio sed pretium lacinia. Vestibulum porttitor finibus orci. Fusce euismod sit amet justo id interdum. Integer imperdiet neque libero, at accumsan velit blandit quis. Interdum et malesuada fames ac ante ipsum primis in faucibus. Duis placerat neque felis, vel porta neque malesuada nec. Ut vehicula ultricies risus.

Nulla laoreet turpis in nibh porta suscipit. In hac habitasse platea dictumst. Cras lacinia a ante cursus congue. Morbi id congue felis. Curabitur porta non dui in euismod. Ut blandit aliquam laoreet. Donec eget leo viverra, accumsan leo finibus, porta orci. Nulla est quam, gravida a erat sit amet, pellentesque fringilla quam. Proin mollis mauris rhoncus porttitor porttitor. Nam ultrices, nibh quis feugiat posuere, mi sem commodo turpis, ac volutpat nisl orci a magna. In id libero eu nulla sollicitudin volutpat. Donec et sapien in leo faucibus laoreet mattis vel sapien.

In vitae dui congue, faucibus purus non, maximus lorem. Quisque efficitur ligula et velit tristique, ac luctus odio varius. Praesent elit nunc, viverra ac iaculis in, lobortis et odio. Vivamus a feugiat nunc. Praesent accumsan porttitor ipsum. Aliquam convallis ultrices dolor at tempor. Praesent malesuada leo nisl, eu imperdiet dui varius eu. Donec non mi dictum ligula viverra ullamcorper. Donec porta dolor odio, vitae vestibulum magna consequat nec. Donec tempor ultricies ipsum nec vulputate. Aliquam id hendrerit enim, et interdum urna. Vestibulum lectus turpis, fermentum non aliquet vel, pellentesque at lorem. Donec a nibh in leo suscipit vestibulum. Mauris ut tortor eu erat mattis vestibulum. Morbi finibus commodo tortor, non tristique est congue id. Etiam pulvinar non elit at feugiat.

Maecenas a semper lacus. Sed elementum auctor ullamcorper. Mauris congue, velit non posuere venenatis, arcu urna tempus augue, vulputate porta felis tortor a mauris. Morbi sed rhoncus lorem. Etiam ultricies magna nisl, et convallis erat tempus eget. Aliquam aliquam scelerisque aliquet. Duis condimentum ornare elit, eu vestibulum felis venenatis at. Quisque congue libero a erat auctor, at suscipit ipsum viverra. Praesent nunc lacus, iaculis in libero nec, dapibus tincidunt mauris. Curabitur condimentum posuere vehicula. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Mauris mattis et nisi sed semper.

Suspendisse vel ante quam. Proin dapibus mauris ultricies orci lacinia, vitae consequat libero aliquet. Quisque a metus cursus, tincidunt purus a, lacinia libero. In in dictum sapien. Vivamus accumsan lectus id urna dictum, ut tempor risus semper. Integer sit amet lacinia est. Aliquam lorem felis, dapibus eget nulla quis, tempor fringilla nulla. Ut porta urna nulla, non pretium justo pretium a. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nunc sed odio ultrices, viverra lacus id, viverra dui.

--- 
Now, back to the typing. Again, things seem to be fine in this case.

What happens now that I have named the file with a .md extension, indicating that the editor should treat it as Markdown? Let's try some lists. I have a suspisicion that lists might be the culprit:

- Here's a list
- It contains things
  - Some nesting
  - And more items
- Top level things
  - And more indents. What's going on? 
