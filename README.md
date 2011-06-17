This is a AsyncLink demo,We implement it use JavaScript now.
How about browser implements this? Use a new <async> tag or modify <a> tag?


    <a href="json.php" target="#foo" async="true" history="true" where="replace">asynclink</a>
    <async url="json.php" target="#foo" history="true" where="replace">asynclink</async>


target represents html dom
async represents this is a async link
history represents browser will add a historyhash for this asynclink
where represents where to append the async content "replace"|"first"|"last"