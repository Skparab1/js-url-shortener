# js-url-shortener
Free to use JavaScript URL shortener, hostable on GitHub pages

## Ultra-fast redirect time (avg redirect time < 1 sec)*
![](ezgif.com-gif-maker(7).gif)

* redirect time will depend on browser speed and computer performance, but the deviation from under 1 second will usually be negligible

## Cool features
- Ultra fast redirect time
- built in animations (randomized)
- message display
- auto refresh (if you click the back button it goest back to and stays on the page, and it it stays for more than 3 second it will automatically refresh and redirect)
- password site access (for this to be useful, you probably want to make your repo private, otherwise, anyone can see the passwords, as well as your auth tokens)
  - for password enabled redirects, user will be prompted to enter password
  - alternate authentication - for you to be able to access all the redirects without the passwords to each one
  - modify username and password in redirects.csv file

### This should ideally be hosted on GitHub pages sites with subpages named "r" or "redirect"
- It's hosted like this on my GitHub pages
- This will make the shortened URL pretty short, <username>.github.io/r/<keyword>
- Alternatively, this repos could be renamed to r and used.
  
# How to use:
  1. Fork this repo and rename it "r" or "redirect" (shorter is better, see above)
    - alternatively, you could copy the folder named "r" or "redirect" and put it in your <username>.github.io repo
  2. Edit the accounts.csv file to add keywords and urls which will be used. (put passwords in the third column, but those are optional and can be left blank
  3. All done! Star this repo if you like it or use it
  
# Other things:
  1. For a more comprehensive explanation, see this article (not done yet)
  2. This Redirector uses 4 realtively simple, which can be easily modified by editing the file.
