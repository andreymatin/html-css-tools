LESS Snippets
================================
A lot of mixins for LESS (http://lesscss.org)

Collection
-----

- Mixins and wrappers
- Transition
- Animation
- Columns
- Transformations 
- Colors
- Shapes
- Flexbox
- Gradients
- Normalize v3.0.2

Usage
-----

1. Copy collection to your LESS folder
2. Add this collection to your main.less:
```scss
@import 'less-snippets/snippets';
```
3. Remove unused mixins from snippets.less


mixins
-----

- .box-shadow (@value)
- .box-shadow-none
- .background-clip(@argument: padding-box)
- .border-radius (@value: 4px)
- .user-select (@value: none)
- .opacity(@value: 1)
- .placeholder-color(@color)
- .text-highlighting(@color, @background)
- .rect(@width, @height)
- .pos(@top, @left)
- .full-page-background(@url)
- .reflect (@length: 50%, @opacity: 0.2){

Transition
-----

- .transition (@value)
- .transition-delay(@delay:0)
- .transition-duration(@duration:200ms)
- .transition-property(@property:all)
- .transition-timing-function(@function:ease)

Animation
-----

- .animation(@args)
- .animation-delay(@delay)
- .animation-direction(@direction)
- .animation-duration(@duration)
- .animation-fill-mode(@mode)
- .animation-iteration-count(@count)
- .animation-name(@name)
- .animation-play-state(@state)
- .animation-timing-function(@function)

Columns
-----

- .columns(@value)
- .column-count(@count)
- .column-gap(@gap)
- .column-width(@width)
- .column-rule(@args)

Transformations 
-----

- .transform(@value)
- .transform-style(@style)
- .scale (@value)
- .rotate (@deg:45deg)
- .skew (@deg, @deg2)
- .translate (@x, @y)
- .translate3d (@x, @y, @z)
- .perspective (@value: 1000)
- .transform-origin (@args)

Flexbox
-----

- .flex-block()
- .flex-inline()
- .flex-flow(@direction: row, @wrap: nowrap)
- .align-content(@alignment)
- .flex-direction(@direction: row)
- .flex-wrap(@wrap: nowrap)
- .justify-content(@justification)
- .align-items(@mode)
- .flex(@args: none)
- .order(@num: 0)
- .flex-grow(@grow: 1)
- .flex-shrink(@shrink: 1)
- .flex-basis(@basis: auto)
- .align-self(@align: auto)

Gradients
-----

- .gradient(@default: #F5F5F5, @start: #EEE, @stop: #FFF)
- .linear-gradient-top(@default,@color1,@stop1,@color2,@stop2)
- .linear-gradient-top(@default,@color1,@stop1,@color2,@stop2,@color3,@stop3)
- .linear-gradient-top(@default,@color1,@stop1,@color2,@stop2,@color3,@stop3,@color4,@stop4)
- .linear-gradient-left(@default,@color1,@stop1,@color2,@stop2)
- .linear-gradient-left(@default,@color1,@stop1,@color2,@stop2,@color3,@stop3)
- .linear-gradient-left(@default,@color1,@stop1,@color2,@stop2,@color3,@stop3,@color4,@stop4)


Useful Resources
-----

- https://github.com/JoelSutherland/LESS-Prefixer
- https://github.com/madebysource/lesshat
- https://github.com/dmitryf/elements

Bower
-----

You can get the latest release using bower.

```ssh
bower install less-snippets
```