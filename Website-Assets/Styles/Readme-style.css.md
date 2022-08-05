If your adding more to the roadmap, youll need to copy & paste this into the ' style.css "  file for this website. 

PLEASE NOTE: Find " @keyframes revealFromLeft {
  0% {
    transform:translateX(-1em);
    opacity:0;
  }
  100% {
    opacity:1;
    transform:translateX(0);
  }
}
" Inside the style.css " file and paste the text below afer making room for what is mentioned above. 


}
.timeline-list li:nth-child( Insert number here ):before {
  animation-delay: Insert delay here s;
}
.timeline-list li:nth-child( Insert numer here ) .content {
  animation-delay: Insert delay here s;
}

It is also recommended for you to to add on .3s to the delay, each time for adding to the timeline list.