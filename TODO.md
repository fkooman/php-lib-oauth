# TODO

- when an approval is revoked, it needs to remove all access tokens and 
  authorization codes with the same parameters as well, not just the
  approval
- in case of code clients a `redirect_uri` is not always needed, it could
  be preregistered. What to do?
- same with scope...some code will badly break I guess?
- strip query parameters from redirect after deleting approval