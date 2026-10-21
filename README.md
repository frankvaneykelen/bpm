# bpm
App to measure the beats per minute of a song by tapping. With decimal values, the min, max and avg values, and a gauge indicating the stability of the measurement. 

## Usage
Open `index.html` in a browser. Tap the button (or press space) in time with the song. Shows BPM rounded to the nearest integer, avg, min, and max to two decimal places, and a stability gauge (based on the variation of the tap intervals). Min and max appear after at least 16 beats have been measured; they start at the current average and track values measured afterward. Reset clears the measurement.
