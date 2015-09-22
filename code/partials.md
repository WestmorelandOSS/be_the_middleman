###### Partial(tagline.haml)
    #tagline HI I LOVE STUFF

###### Haml
    #logo.container
      = render :partial => "tagline"
      %a{href:"www.google.com"} Link to google
      = render :partial => "tagline"

###### HTML
    <div id="logo" class="class">
      <div id="tagline">
        HI I LOVE STUFF
      </div>
      <a href="www.google.com">Link to google</a>
      <div id="tagline">
        HI I LOVE STUFF
      </div>
    </div>
