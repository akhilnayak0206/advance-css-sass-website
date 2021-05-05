# advance-css-sass-website

A simple website using advance CSS and SASS

Learning from Jonas Schmedtmann's Advance CSS and Sass
Notes:

How CSS works behind the scene:
load html -> parse html ------> DOM
                |
                V
                Load CSS  --> Parse CSS
                            |                                             |
                            | Resolve conflicting CSS declaration(Cascade)| -> CSS Object Model(CSSOM)
                            |                                             |
                            | Process final CSS values                    |

DOM + CSSOM -> Render Tree -> Website Rendering: the visual formatting model -> Final Rendered website
