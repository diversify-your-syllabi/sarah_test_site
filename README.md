# sarah_test_site
# Created By Sarah Van Alsten
# December 2019
# Purpose: Building Professional Website to Display Work of Female Statisticians (using Academic theme from Hugo and Blogdown)

To run from R:
Once (first time using) run blogdown::build_site()

Every subsequent time/ after making updates:
run blogdown::serve_site()

New posts can be made in two ways: one, using the blogdown function createpost, or by copying and pasting and existing post folder, then changing the data and text within.

Other notes of use: every site author should have their own folder in the directory content/authors (use same template format as existing author folders)

Additional journal articles can be added in the same way: under content/publication add a folder for each desired addition using existing folders as a template. To have them show up under the content tags, tag them with an appropriate keyword or phrase.

Finally, additional posts can be created under the content/post folder in much the same way. If adding an RMarkdown file, do not knit it - the knit output version is created automatically upon using the serve_site() command. If you accidently forget, just use serve_site() and the new, site generated output should overwrite the knit version.

Under content/home are the available 'widgets' for the site. Many are not in use (at top the unused ones will say active = false) but I have not deleted them in case we would like to use them in the future.

Site can be viewed in browser at:
http://diversify-your-syllabi.rbind.io/
