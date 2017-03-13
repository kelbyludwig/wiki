# The Future of Programming, Bret Victor

* https://www.youtube.com/watch?v=8pTEmbeENF4

* Moore's Law will happen. Hardware will get better. You could just wait, until
  hardware is better but *human thinking* takes time to change.

* Four Big Ideas

    * Coding -> Direct manipulation of data

    * Procedures -> Goals and constraints

    * Text Dump -> Spatial Representations

    * Sequential -> Concurrent

## Direct Manipulation of Data

* Sketchpad - Used to draw pictures on a video display, the computer then could
  e.g. parallelize lines.

* Constraints were dynamically maintained. If you moved, the rectangle around,
  the constraints remained.

* (Tongue in Cheek) In the future, the Internet will not use "markup
  languages", it will be allow for direct manipulation of data.

## Programming Using Goals

* Planner - Procedures meet goals. Can also get procedures from goals. 

    * "Goals" - The results you want

    * "Procedures" - Strategies for meeting goals

* Prolog - Expressing programs as goals

* Pattern Matching - Snobol, regular expressions

* Goal directed programming is important because of the "communicating with aliens" problem.

    * "How do you start communicating with uncorrelated sapient beings?"

    * You have to negotiate a shared language. 

    * Goals are important here because aliens won't know the procedures.

* "API"s won't work because code is tied to a particular service.

* Human is doing the low-level details, stuff a computer should be doing.

## Spatial Representation of Information

* Programs are lines of texts. That makes sense when the storage media is linear.

* NLS - Mouse! Different views of data.

* GRAIL - programming using flow charts

* SMALLTALK - source code is text, but the text is organized based on syntax
  structure

* "Very confident we won't be writing code in text files."

## Concurrent Programming

* Von Neumann architecture leads to very linear programming model

* To maximize throughput, parallelize processors

* Threads and Locks are what we use "today"

    * Doesn't scale, pretty low level

* What would work? "The Actor Model"

    * You have a bunch of processes doing their own thing

    * Processes are sending data to each other

## Conclusions

* It would be a shame if these interesting paradigms were forgotten, or unused.

* If you grow up with dogma, its hard to break out of it.

* "[Back then] No one knew what programming was supposed to be", so they tried
  a bunch of models.

* "The most dangerous thought you could have as a creative person is to think
  you know what you are doing. Because once you think you know what you are
  doing, you stop looking for new ways."
