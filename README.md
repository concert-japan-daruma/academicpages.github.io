1. Change the personal/project information in */_config.yml*.
2. Remove the unnecessary footer items in */_includes/footer.html*.
3. Remove the author information at the sidebar in */_config.yml* under Site Author.
4. Change the menu in */_data/navigation.yml*.
	- News - portfolio
	- Publications
		- Journal - publications
		- Conference - posts
	- WPs and Deliverables 
		- WPs: */_pages/talks.html*
		- Deliverables - talks
	- Consortium - teaching
5. Edit the Home or About me page in */_pages/about.md*.
6. Change the page path by modifying the url in */_data/navigation.yml*, the permalink in the respective *.html* or *.md* in */_pages*.
7. Change the icon in */_includes/head/custom.html*.
8. Remove the author photo ellipses sidebar in */_layouts/single.html* and */_layouts/talk.html* after commenting line 18, */_includes/sidebar.html* line 8 - line 16.