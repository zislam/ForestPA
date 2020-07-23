# ForestPA

Class implementing decision forest algorithm Forest PA, using bootstrap samples and penalized attributes. Uses and depends on SimpleCart.

For more information, see:

*Adnan, Md Nasim, Md Zahidul Islam (2017). Forest PA: Constructing a Decision Forest by Penalizing Attributes used in Previous Trees. Expert Systems with Applications.*

## BibTeX:
```
\article{adnan2017forest,
  title={Forest PA: Constructing a Decision Forest by Penalizing Attributes used in Previous Trees},
  author={Adnan, Md Nasim and Islam, Md Zahidul},
  journal={Expert Systems with Applications},
  year={2017},
  publisher={Elsevier}
}
```
## Installation

Either download ForestPA from the Weka package manager, or download the latest release from the "Releases" section on the sidebar of Github. A video of how to install and use the package can be found [here](https://www.youtube.com/watch?v=Q1sea2--xy8&t=377s)

## Compilation / Development

Set up a project in your IDE of choice, including weka.jar and simpleCART.jar as compile-time libraries. simpleCART.jar is available in the Weka package manager.

## Valid options are: 

`-T &lt;num trees`
 Number of trees requested in the forest.
 (default 10)

`-M &lt;min no`
 The minimal number of instances at the terminal nodes of each SimpleCart.
 (default 2)

`-N &lt;num folds`
 The number of folds used in the minimal cost-complexity pruning for each SimpleCart.
 (default 5)
