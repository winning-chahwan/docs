You need to provide a way for your application to recognize if the user is authenticated. To do that, use the `isAuthenticated` method to check if the user's access token has expired. The user is no longer authenticated when the expiry time of their access token passes.