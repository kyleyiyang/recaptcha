# recaptcha

When adding recaptcha to Contact Form 7, the recaptcha v3 did not work with an error loading recaptcha_v3 javascript from Google api.

Solutions:

1. Install a plugin: ReCaptcha v2 for Contact Form 7
2. In the contact ---> reCaptcha setting, select version 2 from google.com (of course the reCaptcha Api Keys should be already integrated in the "Integration" setting).
3. If all are successful, add the shortcode [recaptcha] before submit button (see the php file).
 
