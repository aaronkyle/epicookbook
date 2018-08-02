---
title: 'Javascript'
permalink: 'chapters/sir/js'
previouschapter:
  url: chapters/sir/octave
  title: 'Octave'
nextchapter:
  url: chapters/stochastic
  title: 'Simple stochastic models'
redirect_from:
  - 'chapters/sir/js'
---
## SIR model using Javascript

[Link to Observable notebook](http://beta.observablehq.com/@epichef/deterministic-sir-model)

<script type="application/javascript">

function resizeIFrameToFitContent( iFrame ) {

    iFrame.width  = iFrame.contentWindow.document.body.scrollWidth;
    iFrame.height = iFrame.contentWindow.document.body.scrollHeight;
}

window.addEventListener('DOMContentLoaded', function(e) {

    var iFrame = document.getElementById( 'iFrame1' );
    resizeIFrameToFitContent( iFrame );

    // or, to resize all iframes:
    var iframes = document.querySelectorAll("iframe");
    for( var i = 0; i < iframes.length; i++) {
        resizeIFrameToFitContent( iframes[i] );
    }
} );

</script>

<iframe src="../../observables/deterministic-sir-model/index.html" frameBorder="0" scrolling="no"></iframe>
