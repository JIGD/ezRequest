ezRequest
=========

Requests made easy and readable on java.


Maybe change the way the post/get is set on the submit? eliminate the Submit and set it as post or get?
Submit("get").To("this address").withParams("bla","bla");

Login.To("someAddress").usingUsername("user").usingPassword("unsafepassword").getCSRFToken("CSRF_PROTECTION");

HttpResponse response = Submit("post").To("target address").withBody(LongStringVar).asHtml();
