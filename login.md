---
layout: page
title: Login
subtitle: ''
img_path: ''

---

<form name="login-form" method="POST" id="signup-form" class="login-form" ms-login="true">
<p class="form-row">
<label class="form-label">Email address</label>
<input type="email" name="email" class="form-input" ms-field="email">
</p>
<p class="form-row">
<label class="form-label">Password</label>
<input type="password" name="password" class="form-input" ms-field="password">
</p>
<input type="hidden" name="form-name" value="login-form" />
<p class="form-row form-submit">
<button type="submit" class="button">Sign In</button>
</p>
<p>
Forgot your password? Need to <a href="#" ms-forgot="true">reset it?</a>
</p>
</form>