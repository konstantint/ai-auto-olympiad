# AI plays olympiads with itself

The repository contains a few Colab notebooks where an LLM is first tasked to generate an informatics olympiad task,
along with tests, and then (in another session) asked to solve it.

The notebook validates that the task "author" has created reasonable tests, and that the task "solver" has managed
to pass these.

The saved notebooks are basically copies of the same template with minor modifications in the prompt or
tuning of the output processing in case the generated output wasn't ideal. Rerunning them makes more tasks,
changing the prompt can affect the topic, complexity, storyline, format, etc.

Try it, it's fun.

The same notebooks in Colab:
* [Baltic trade routes](https://colab.research.google.com/drive/1tsbiVALQ5A2i3Q1JpAvAO_jAF4U4VXX7)
* [Island trading](https://colab.research.google.com/drive/14zfJCqMt5-rcsLSF43XJobvIJpobuXvg)
* [Ancient runes translation](https://colab.research.google.com/drive/1-4e7b5-SlxGBb_JP0KtuY1yqEr81NfgV)
* [Simple DNA Segments (15-liner)](https://colab.research.google.com/drive/11KW_VGyTXTqpTOSQBHo9xGGlDDe5SvDN)
