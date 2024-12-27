# sr-only
Hide labels and titles (and everything else inside the html) that you just want to show to screen readers, but not for the regular user.

We are going to use the in the HTML tag the class="sr-only".
And in the CSS the selector:

<pre>
.sr-only {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    white-space: nowrap;
    border-width: 0;
}
</pre>

* sr-only stands for "screen reader only"
