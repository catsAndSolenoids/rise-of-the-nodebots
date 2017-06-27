#code
<div>
        <pre><code class="javascript" data-trim="" class="javascript">
var five = require( 'johnny-five' ); // to talk with the arduino
var board = new five.Board(); // initiating a board object

//document ready, johnny style (the document is a board)
board.on( 'ready', function() {
    // Pin 13 has an LED connected on most Arduino boards.
    // give it a name:
    var led = new five.Led({
        pin: 13
    });

    // the loop routine runs over and over again
    // forever to "flash/blink/strobe" an led
    board.loop( 100, function() {
        led.toggle();
    });
});

        </code></pre>
        </div>
