# Understanding http-server

- Using `http.Handler` to create web servers
- Use `http.HandlerFunc` to turn ordinary functions into `http.Handler`s
- Use `httptest.NewRecorder` to pass in as a ResponseWriter to spy on the responses your handler sends
- Use `http.NewRequest` to construct the requests you expect to come in to your system

