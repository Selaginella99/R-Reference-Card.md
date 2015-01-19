- unique(x, incomparables = FALSE, ...)

unique(x) if x is a vector or a data frame, returns a similar object but with the duplicate elements suppressed.

---

- strsplit(x, split, fixed = FALSE, perl = FALSE, useBytes = FALSE)

Split the elements of a character vector x into substrings according to the matches to substring split within them. 

---

- unlist(x, recursive = TRUE, use.names = TRUE)

Given a list structure x, unlist simplifies it to produce a vector which contains all the atomic components which occur in x. 

---

- grep(pattern, x, ignore.case = FALSE, perl = FALSE, value = FALSE, fixed = FALSE, useBytes = FALSE, invert = FALSE)

grepl(pattern, x, ignore.case = FALSE, perl = FALSE, fixed = FALSE, useBytes = FALSE)

sub(pattern, replacement, x, ignore.case = FALSE, perl = FALSE, fixed = FALSE, useBytes = FALSE)

gsub(pattern, replacement, x, ignore.case = FALSE, perl = FALSE, fixed = FALSE, useBytes = FALSE)

regexpr(pattern, text, ignore.case = FALSE, perl = FALSE, fixed = FALSE, useBytes = FALSE)

gregexpr(pattern, text, ignore.case = FALSE, perl = FALSE, fixed = FALSE, useBytes = FALSE)

regexec(pattern, text, ignore.case = FALSE, fixed = FALSE, useBytes = FALSE)

grep, grepl, regexpr and gregexpr search for matches to argument pattern within each element of a character vector: they differ in the format of and amount of detail in the results. sub and gsub perform replacement of the first and all matches respectively. [regexec](http://127.0.0.1:16406/library/base/html/grep.html).

---

- write(x, file = "data", ncolumns = if(is.character(x)) 1 else 5, append = FALSE, sep = " ")

The data (usually a matrix) x are written to file file. If x is a two-dimensional matrix you need to transpose it to get the columns in file the same as those in the internal representation. 

- paste (..., sep = " ", collapse = NULL)

Concatenate vectors after converting to character. 

*e.g.*
x = 'abc'
y = 'cba'
z = c('abc', 'cba')

paste(x, y, sep = ','); paste(z, collapse = ',')

---







