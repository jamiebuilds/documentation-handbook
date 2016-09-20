# How to write high quality friendly documentation that people want to read

For the last few years I have written a lot of documentation for projects like
Babel or Flow, blog posts, and guides such as these:

- https://github.com/thejameskyle/the-super-tiny-compiler
- https://github.com/thejameskyle/itsy-bitsy-data-structures
- https://github.com/thejameskyle/babel-handbook

I've tried to focus on the way that I write in order to make it more
approachable and more useful to everyone. There are a number of things that I
have learned over the years that I believe makes for high-quality and friendly
documentation.

> **Note:** Some of this only really applies when you are talking about things
> that require tons of documentation. Try to adapt this advice to fit what you
> are working on best.

Here they are as one massive list:

#### In general...

- Keep a lighthearted friendly tone. Don't spend time trying to prove how smart
  you are. Treat the reader as a close friend who doesn't have a lot of
  knowledge about the topic but is very interested.
- Don't assume prior knowledge about the topic. If you want to appeal to a
  large audience (i.e. not a research paper) then you are going to have people
  with very diverse backgrounds.
- Don't use words like "obviously" or "basically", I promise you will never
  *need* to. Just say what needs to be said in simple straight forward
  language. Never ever talk down to people (both of those words do, as well as
  others).
- Don't use idioms. Speak using more formal terms that are well defined. This
  makes it easier for non-native-english speakers and for translations to be
  written. If you do, you won't just knock it out of the park, you'll do a
  really good job.
- Use words that are easier to understand and translate (i.e. "list" instead
  of "enumerate"). Don't worry that you're being slightly more precise using a
  bigger word, think about how it will sound to someone unfamiliar with the
  topic.
- Keep things brief. Avoid giant paragraphs, breaking them apart into multiple
  paragraphs each with a clear point. If you are writing really long
  paragraphs, it's most likely that you aren't doing a good job explaining what
  you mean.
- Link to other places in the documentation often ***but*** only for additional
  information. Readers should not have to navigate through several pages to
  find the information that they need about one specific thing. Just inline the
  immediately relevant information and link off if they want to know more.
- Reuse the same small set of examples as much as possible, keep presenting the
  same problem and building on top of it. Don't make the user keep thinking
  about new problems, people can only focus on so many things. If you need to
  keep coming up with new examples, you haven't started in a good place, start
  over and come up with a better one.

#### When writing guides...

- Use as many code/cli/etc examples as possible, *show* the reader what you
  mean. This makes things far easier to translate and is generally much easier
  to follow than walls of text. Even if you aren't going to discuss the code
  directly it's good for giving context.
- Use headings frequently. This breaks things up when reading and often it is
  good for linking to specific information.
- If writing with multiple pages, think about how a single page leads into the
  next, point the user to the next page and make sure it follows naturally.
- Gently introduce a guide before diving into technical details. This gives
  context and readers are more likely to stay engaged longer.

#### When writing api documentation...

- Think about API docs like they are guides on how to use them. Type signatures
  for input and output and a vague description isn't enough to be useful.
- Add information explaining the purpose of a group of APIs before diving into
  them. Also add any other relevant information or caveats. People are far more
  likely to read it this way.
- Use shared terminology with API names, examples, and explanations. Call
  something a single name no matter where you are referring to it, and name
  things
- Don't try to solve real world scenarios in code examples if they become any
  more complicated than the API already is. Do not implement algorithms, do not
  add a bunch of noisy implementation details that doesn't aid the user.
- Keep code examples extremely short. Your target should be ~3-5 lines of code,
  every line past that is a count against you. Think hard about the examples
  you are using.

#### Absolutely...

- Never use terms that are offensive to any group. There will never be a good
  reason to.
- Do not use gendered terms. Pronouns like he/she/her/him and gendered terms
  like actress/actor/waiter/waitress should all be thrown out and you should
  avoid using any terms or phrases that don't necessary refer directly to
  gender but have gendered connotations. For example, words "pretty", "curvy",
  "moody", or "bossy" all refer to women far more often than they do men.
- Avoid examples using people. You end up sounding like you're talking to
  children and it's easy to create examples that place one group of people over
  another (i.e. "Susan went to her project manager Tim..."). So as a more
  generalized rule, use examples that don't involve people.
- Follow other guidelines outlined in documents like the
  [Contributors Covenant](http://contributor-covenant.org/).

---

This is a living guide for myself and others as I learn more about writing
documentation. I hope it is helpful to others in its current state. If you have
any suggestions, feel free to open an issue or pull request on GitHub and let
me know.

Have fun writing!

---

[![cc-by-4.0](https://licensebuttons.net/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)
