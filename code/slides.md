!SLIDE center
# Demo #


!SLIDE
# Create new game #

	@@@ bash 
		$ gamebox new floopy_bird
		$ cd floopy_bird
		$ bundle install
		$ rake

~~~SECTION:notes~~~
  Builds out basic structure
~~~ENDSECTION~~~

!SLIDE center
# Animation  #
~~~SECTION:notes~~~
  set size in game.yml |
  player => bird |
  stage |
  animated_behavior |
  graphical
~~~ENDSECTION~~~


!SLIDE center
# Fly / fall physics #
~~~SECTION:notes~~~
  add physics behavior |
  add fly/glide animations |
~~~ENDSECTION~~~


!SLIDE center
# Flaps on key input #
~~~SECTION:notes~~~
  add flappy behavior
  add map controller in stage
~~~ENDSECTION~~~

!SLIDE center
# Camera follow #

!SLIDE center
# Rotation  #

!SLIDE center
# Sound  #

!SLIDE center
# Music #

!SLIDE center
# Pipe generation / clean up #

!SLIDE center
# Define pipe actor & view #

!SLIDE center
# Die from pipe #

!SLIDE center
# Background #

!SLIDE center
# Scoring #

!SLIDE center
# Die by ground #

!SLIDE center
# No flying over pipes #

!SLIDE center
# Wait for first input to start #

!SLIDE
# Packaging #
	@@@ bash 
		$ rake package:osx_app:tar_gz
		$ rake package:windows_folder:exe
		$ rake package:source:tar_gz


!SLIDE
# Ideas #
## power ups ##
## speed up on each pipe ##
## moving pipes ##
## explode on collision ##
