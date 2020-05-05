---
template: page
title: 聯絡資訊
slug: contacts
draft: false
---
 <form name="Contact Form" method="POST" data-netlify-recaptcha="true" data-netlify="true" action="/pages/success">
  <p>
    <label>姓名：<input type="text" name="name" /></label>   
  </p>
  <p>
    <label>您的E-mail：<input type="email" name="email" /></label>
  </p>
    <label>想說的話：<textarea name="message"></textarea></label>
  </p>
<div data-netlify-recaptcha="true"></div>
  <p>
    <button type="submit">傳送</button>
  </p>
</form>