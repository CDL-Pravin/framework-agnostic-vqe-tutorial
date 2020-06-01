# A Framework Agnostic VQE Tutorial

If you're just getting started in quantum computing, it might sometimes feel a little overwhelming to dive straight into understanding the Variational Quantum Eigensolver (VQE).

I'm here to tell you it can be done! Although for me, I found it a little difficult to learn about the actual quantum computing concepts with a framework obscuring what's actually happening under the hood.

So this is a very down-to-earth tutorial that will take you through a toy example of VQE using only generic python packages. I'll do my very best not to introduce new concepts without either explaining them or pointing you to a reference.

## Who this is for

The purpose of this tutorial is actually threefold:

1. Learn the basics of VQE
2. Get hands-on with basic concepts from quantum computation. This is why we would bother coding from scratch instead of using a quantum simulation library.
3. Get some sense of how our toy example relates (and doesn't relate) to real VQE.

As such, the following points best describe someone who'd benefit from this tutorial:

- You're familiar with Python and widespread packages such as numpy.
- You're newly familiar with the basics of quantum computing, but you'd like to get a more hands-on feel for it all.
- The following terms aren't new or (overly) intimidating to you: Wavefunction; Qubit; Hamiltonian; State preparation; Pauli operator; Bloch sphere; Quantum gate; Projection measurement; Observable.
- _Not super important_: You're familiar with the concept of [computational optimisation](https://en.wikipedia.org/wiki/Mathematical_optimization). If you're not, it should take you 15-30 mins of googling to get a good enough idea.

## How to use this tutorial repo

Everything should take you 2 hours or more (depending on how many side quests you decide to go on).

1. Clone into your local machine. (skip to step 3 if you want to use Google Colab)

   ```
   git clone https://github.com/alexander-soare/framework-agnostic-vqe-tutorial.git
   ```

2. Install requirements. (skip to step 3 if you want to use Google Colab)

   ```
   pip install -r requirements.txt
   ```

3. Start with [the prereading](./01_Prereading.md).

4. Then open up the **_02_Tutorial.ipynb_** notebook in your favorite environment, or:

   (a) click here to open it in [Google Colab](https://colab.research.google.com/github/alexander-soare/framework-agnostic-vqe-tutorial/blob/master/02_Tutorial.ipynb)

   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alexander-soare/framework-agnostic-vqe-tutorial/blob/master/02_Tutorial.ipynb)

   (b) or [preview it on Jupyter nbviewer](https://nbviewer.jupyter.org/github/alexander-soare/framework-agnostic-vqe-tutorial/blob/master/02_Tutorial.ipynb)

   _Note that the Github previewer lacks full markdown support for equations so I would recommend using one of the above methods instead._

5. **Feel free to make use of this repo's [Github Issues](https://github.com/alexander-soare/framework-agnostic-vqe-tutorial/issues) as a questions and discussions forum!**

6. Share this with others by linking to the current page: https://github.com/alexander-soare/framework-agnostic-vqe-tutorial.

## Acknowledgements (also alternative resources for you)

I've acquired most of my knowledge from the following resources. This work is a reflection of that.

- Insightful blog post with deep dives into ansatzes and the variation principle: https://www.mustythoughts.com/variational-quantum-eigensolver-explained (would definitely recommend reading more posts from this site)
- Excellent notebook tutorial. Nice and concise. Similar narrative to this one but using the qiskit library: https://github.com/DavitKhach/quantum-algorithms-tutorials/blob/master/variational_quantum_eigensolver.ipynb
- Official qiskit tutorial: https://qiskit.org/textbook/ch-applications/vqe-molecules.html
- VQE paper: [A variational eigenvalue solver on a quantum processer](https://arxiv.org/pdf/1304.3061.pdf)

Also, a very appreciative thankyou to the following people who have helped me
review this tutorial:

- [Michał Stęchły](https://www.mustythoughts.com/about)
- [Davit Khachatryan](https://github.com/DavitKhach)
