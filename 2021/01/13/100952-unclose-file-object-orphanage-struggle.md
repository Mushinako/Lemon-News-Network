# Local Unclosed File Object Orphanage Struggles as More People Start to Learn Python

Local orphanage director Mike Bart told Lemon News Network that he had seen the number of unclosed
file objects rocket in the past year. "Many people are starting to learn Python for the first time,
and forgetting to properly close a file object is an easy and common mistake."

Mr. Bart indicated that the number of unclosed file objects admitted to his orphanage rose by 700%
in the last year, eclipsing the previous record set in 2016, when a coder accidentally put an
`open` within a loop, resulting in the sudden spike of over 16 million unclosed file objects before
the operating system put it to a halt.

"Many people expect Python to object the file closing automatically, but that's not how Python
always works." Mr. Bart commented as he guided an LNN reporter through the gallery of photos of
him and the orphan file objects, "So please be a responsible parent. Remember to `.close()` the
file object, or use `with` whenever possible."

*Reported by Mushy on 2020-01-13 at 10:09:52 PST*
