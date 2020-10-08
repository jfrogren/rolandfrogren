+++
title = "Beställ boken"
+++

<form name="Bestall boken" method="POST" data-netlify="true">
  <p>
    <label>Ditt namn: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Din epost: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Din roll: <select name="role[]" multiple>
      <option value="leader">Leader</option>
      <option value="follower">Follower</option>
    </select></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>

