# Cat-NG-Project
<!DOCTYPE html>

<html lang="en">
  <head>
    <meta charset="utf-8"
    <title>CatPhotoApp</title>
  </head>
  <body>
    <main>
      <h1>CatPhotoApp</h1>
      <section>
        <h2>Cat Photos</h2>
        <!-- TODO: Add link to cat photos -->
        <p>See more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a> in our gallery.</p>
        <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
      </section>
      <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
          <figcaption>Cats <em>love</em> lasagna.</figcaption>  
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>  
        </figure>
      </section>
      <section>
        <h2>The best to worst things to feed your cat</h2>
        <ol>
          <li>Name Brand Cat Food</li>
          <li>Tuna</li>
          <li>Rocks</li>
          <li>Gun Ammo</li>
          <li>Battery Acid</li>
        </ol>
      </section>
      <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
          <fieldset>
            <legend>Does your cat love or hate dogs?</legend>
            <label><input id="Love" type="radio" name="Love-Absolutely Hate" value="Love" checked> Love</label>
            <label><input id="Absolutely Hate" type="radio" name="Love-Absolutely Hate" value="Absolutely Hate" checked> Absolutely Hate</label>
          </fieldset>
          <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor" checked> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
          </fieldset>
          <fieldset>
            <legend>What's your cats favorite toy?</legend>
            <input id="Nerf Guns" type="checkbox" name="toy?" value="Nerf Guns" checked> <label for="Nerf Guns">Nerf Guns</label>
            <input id="Spiderman Web-Shooters" type="checkbox" name="toy?" value="Spiderman Web-Shooters" checked> <label for="Spiderman Web-Shooters">Spiderman Web-Shooters</label>
            <input id="Donald Trumps Hair" type="checkbox" name="toy?" value="Donald Trumps Hair" checked> <label for="Donald Trumps Hair">Donald Trumps Hair</label>
          </fieldset>
          <fieldset>
            <legend>What's your cat's personality?</legend>
            <input id="loving" type="checkbox" name="personality" value="loving" checked> <label for="loving">Loving</label>
            <input id="lazy" type="checkbox" name="personality" value="lazy"> <label for="lazy">Lazy</label>
            <input id="energetic" type="checkbox" name="personality" value="energetic"> <label for="energetic">Energetic</label>
            </fieldset>
          <input type="text" name="catphotourl" placeholder="cat photo URL" required>
          <button type="submit">Submit</button>
        </form>
      </section>
    </main>
    <footer>
      <p>
        No Copyright - <a href="https://www.freecodecamp.org">freeCodeCamp.org</a>
      </p>
    </footer>
  </body>
</html>
