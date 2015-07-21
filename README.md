# page-title

A Polymer element for updating the title of a webpage declaratively, possibly
automatically, using Polymer bindings. Example:

    <page-title base-title="zacharytamas" title="Home"></page-title>

Or something more complex using bindings:

    <my-blog>
      <!-- inside Local DOM -->
      <page-title base-title="MyBlog"
        title="{{currentPost.title}}"></page-title>
    </my-blog>
