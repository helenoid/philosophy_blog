---
Title: Category Meta
Sort: 0
---

 You can add a file called meta (with no extension) in the category foler. This file must be specified in [YAML](http://www.yaml.org/spec/1.2/spec.html) and contains meta data about the category. The following meta items affect how Polymicrobial Systems works:

 * Title - This variable will override the title based on the folder name.
 * Sort - This variable will affect the sorting of the categories.
 * ShowOnHome - Optional. If false, categoru won't show on the home page. Default behavior can be changed through `config.show_on_home_default`.
 * Description - Optional. This variable will provide a variable to be used in the templates, for example in the hompage, to enhance and clarify the content of the category.

 Note that `config.show_on_home_default` sets the default behavior for pages too.
