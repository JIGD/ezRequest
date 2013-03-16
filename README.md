ezRequest
=========

Requests made easy and readable on java.

Submit(get).To("this address").withParams("bla","bla");

Login.To("someAddress").usingUsername("user").usingPassword("unsafepassword").getCSRFToken("CSRF_PROTECTION");

HttpResponse response = Submit(post).To("target address").withBody(LongStringVar).asHtml();
