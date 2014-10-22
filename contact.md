---
title: Contact
layout: default
---

<h2>For closing documents</h2>
<p>For closing requests please write to <a href="mailto:support@hoasteward.com">support@hoasteward.com</a> or complete the form at <a href="http://hoasteward.com/closing">hoasteward.com/closing</a><p>

<h2>To contact the Board of Directors use the form below</h2>

<p>
  Forms like this are a little impersonal, but they help to 
  get the message to the correct people while protecting 
  against some of the unfortunate truths of the internet.
</p>

<form method="POST" action="http://savannahgreenurbana.org/cgi/contact.pl">
  <fieldset>
  <legend>
   All fields are required (only the math and email address fields are strict, though)
  </legend>


  <p>
    <label for="request-type">
    Type of Request
    </label>
    <SELECT size="1" name="request-type">

      <OPTGROUP label="To the President">
      <OPTION selected value="general">General Information</OPTION>
      <OPTION value="construction">Construction Approval</OPTION>
      <OPTION value="complaint">Complaint</OPTION>
      </OPTGROUP>

      <OPTGROUP label="To the Secretary">
      <OPTION value="dues">Dues Status Request</OPTION>
      </OPTGROUP>

    </SELECT>
  </p>


  <p>
    <label for="name">
      Your Name
    </label>
    <input class="input-text" type="text" name="name" />
  </p>


  <p>
    <label for="email">
    Email Address
    </label>
    <input class="input-text" type="text" name="email" />
  </p>


  <p>
    <label for="email2">
    Confirm Email Address
    </label>
    <input class="input-text" type="text" name="email2" />
  </p>


  <p>
    <label for="property">
    Property Address
    </label>
    <input class="input-text" type="text" name="property" />
  </p>


  <p class="explanatory-text">
    (The street name will likely be one of the following:
    Florida Avenue,
    Smith Road,
    Ogelthrope Avenue,
    Montgomery Street,
    Abercorn Street.)
  </p>


  <p>
    <label for="message">
    Your Message
    </label>
    <textarea class="input-text", name="message"></textarea>
  </p>


  <p>
    <label for="anti-spam">
    2 + 5 =
    </label>
    <input class="input-text" type="text" name="anti-spam" />
  </p>


  <p class="explanatory-text">
    (Please help prevent spam by answering the simple math problem.)
  </p>


  <p class=hidden>
    <label for="anti-spam-answer">
    Anti-Spam Answer
    </label>
    <select size="1" name="anti-spam-answer">
      <option selected value="7">7</option>
    </select>
  </p>


  <p>
    <input class="submit" type="submit" value="Send the Message">
  </p>


  </fieldset>
</form>

