# test
SCSS (pour progressbar.css):

@keyframes scroll {
    @for $x from 0 through 100 {
      #{$x}% {
        background-size: #{$x}vw 10px;
        content: '#{$x}%';
      }
    }
  }