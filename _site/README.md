# familiar.energy

Familiar.energy is a collection of ideas and events with versatile shapes: great metaphors that people have already shared, for example; or weirdly congruent, adjacent, and uncanny concepts that feel like metaphors waiting to be made.

The idea for this site came chiefly from [Metaphors We Live By](https://www.google.co.uk/books/edition/Metaphors_We_Live_By/r6nOYYtxzUoC), by Lakoff and Johnson, and the [Shape Rotators meme](https://roonscape.ai/p/a-song-of-shapes-and-words).

## How it works

1. [reading-list-sync](https://github.com/dave-regan/reading-list-sync) runs on script.google.com at midnight every night, caching my reading list as a JSON file
2. [Jekyll deploy action](https://github.com/jeffreytse/jekyll-deploy-action) runs shortly after, executing a build using [Jekyll Get JSON](https://github.com/brockfanning/jekyll-get-json) to output the site.

## To do

1. Add a random entry at the top to keep things fresh (Liquid can't sample random items from a collection, though, so I'll need to update reading-list-sync to pass entries as an array instead).
2. Add citations for ideas and events
3. Break down the composition of good metaphorical candidates so they can be easily rotated for design ideation workshops, etc.
