<section id="user-input">
    <!--- This is the main user input section a form tag wraps the inputs we want to collect -->
    <form method="get">
        <div>
            <!-- This is a single input, it has a label and a input field for the user to enter information into. The name signifies the variable the input will be stored in -->
            <label for="adj1">ADJECTIVE</label>
            <input type="text" name="adj1" placeholder="adjective" />
        </div>
            <label for="plnoun1">PLURAL NOUN</label>
            <input type="text" name="plnoun1" placeholder="plural noun" />
        <div>
            <label for="noun1">NOUN</label>
            <input type="text" name="noun1" placeholder="noun" />
        </div>
            <label for="adj2">ADJECTIVE</label>
            <input type="text" name="adj2" placeholder="adjective" />
        <div>
            <label for="body1">PART OF THE BODY</label>
            <input type="text" name="body1" placeholder="part of the body" />
        </div>
            <label for="adj3">ADJECTIVE</label>
            <input type="text" name="adj3" placeholder="adjective" />
        <div>
            <label for="plnoun2">PLURAL NOUN</label>
            <input type="text" name="plnoun2" placeholder="plural noun" />
        </div>
            <label for="body2">PART OF THE BODY</label>
            <input type="text" name="body2" placeholder="part of the body" />
        <div>
            <label for="adj4">ADJECTIVE</label>
            <input type="text" name="adj4" placeholder="adjective" />
        </div>
            <label for="adv1">ADVERB</label>
            <input type="text" name="adv1" placeholder="adverb" />
        <div>
            <label for="noun2">NOUN</label>
            <input type="text" name="noun2" placeholder="noun" />
        </div>
            <label for="body3">PART OF THE BODY - PLURAL</label>
            <input type="text" name="body3" placeholder="part of the body - plural" />
        <div>
            <label for="adv2">ADVERB</label>
            <input type="text" name="adv2" placeholder="adverb" />
        </div>
        <!-- Button for the user to click when submiting the form -->
        <input type="submit" />
    </form>
</section>

<!-- The madlib we will populate -->
<section id="madlib">
    <!-- we wrap the mad lib in a paragraph tag, inside of this we will need something to place the text into that the user submits. I am using a span because it displays on the page inline instead of something that would cause a linebreak to happen, such as another p tag or div.  The id is a tag we can use to specify which field this is, I am naming it the same as the name on the form input to keep things simple, it could be anything as long as it is unique. -->
    <h1>THE POWER OF THE FORCE</h1>
    <p>The Force is a mystical, <span id="adj1"></span> power. As Jedi Master Obi-Wan Kenobi once said, “The Force is an energy field, created by all living <span id="plnoun1"></span>, that surrounds us, penetrates us, and binds the <span id="noun1"></span>.” Using the power of the Force, a Jedi can do many <span id="adj2"></span> things, like using the Force to exercise <span id="body1"></span> control over <span id="adj3"></span>-minded <span id="plnoun2"></span>. A Jedi can also use the Force to move objects with their <span id="body2"></span>. It doesn’t matter how <span id="adj4"></span> these objects are; it only matters how <span id="adv1"></span> the Jedi believes in the Force. Most importantly, the Force teaches a Jedi to rely on their feelings. As Obi-Wan Kenobi told his student Luke <span id="noun2"></span>-Walker: “Your <span id="body3"></span> can deceive you. Don’t trust them.” Instead, a Jedi should <span id="adv2"></span> trust the Force.</p>
</section>

<!-- We will be putting code inside of script to handle the logic of how to handle the madlib population -->
<script>

</script>