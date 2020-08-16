<p align="center">
  <img src="images/logo_pyBlackScholesAnalytics.png" width="500" title="hover text" stlye="max-width:10%;">
</p>

# pyBlackScholesAnalytics

[**pyBlackScholesAnalytics**](https://github.com/gabrielepompa88/pyBlackScholesAnalytics) is a Python package for implementing analytics for options and option strategies under the Black-Scholes Model for educational purposes.

# Summary

[**pyBlackScholesAnalytics**](https://github.com/gabrielepompa88/pyBlackScholesAnalytics) package is a Python package designed to use the well known Black-Scholes model 
to evaluate price, P&L and greeks of European options (both plain-vanilla and simple equity exotics 
such as cash-or-nothing Digital options), as well as simple option strategies built on them.

The package has been developed as a spin-off project of the ["IT for Business and Finance"](https://github.com/gabrielepompa88/IT-For-Business-And-Finance-2019-20) class held at the University of Siena for the Master degree in Finance in 2020.

[**pyBlackScholesAnalytics**](https://github.com/gabrielepompa88/pyBlackScholesAnalytics) places itself in the middle between the coding style and level of a master student and that required for a junior quant at an investment bank. The aim is to address the gap between the two providing a playground 
for students to master financial concepts related to options and option strategies and implementing a dedicated comprehensive
object-oriented architecture.

# Contents:

The current version (0.0.1) of the package features the following modules:

- `options`: definitions for `EuropeanOption` abstract base-class as well 
as `PlainVanillaOption` and `DigitalOption` derived classes

- `portfolio`: definition of `Portfolio` class implementing analytics for portfolios of options

- `plotter`: definitions for `Plotter` abstract base-class as well 
as `OptionPlotter` and `PortfolioPlotter` derived classes

- `utils`: definition of general utility functions

- `numeric_routines`: definition of `NumericGreeks` class implementing option greeks through finite-difference methods

# Resources 

As far as the educational purpose is concerned, I find the [**pyBlackScholesAnalytics**](https://github.com/gabrielepompa88/pyBlackScholesAnalytics) package itself helpful as much as the way in which its final version can be progressively built. In my experience, the constructive approach is ubiquitous in the real life of a Quant/Strat: a business need is first formulated by a trader or another stakeholder, then tackled by the Quant/Strat team with an _ad hoc_ analysis, then a tactic short-term implementation of the response is produced and, finally, a strategic and robust long-term solution is designed and implemented. For this reason, the package is complemented by a series of 4 Tutorials in the form of [Jupyter Notebooks](https://github.com/gabrielepompa88/pyBlackScholesAnalytics/tree/master/Notebook_Tutorials) and [Youtube Videos](https://www.youtube.com/channel/UC77o5i2ePrXjwlQQLQeYsBw/playlists). These tutorial aim to present the package step-by step in a constructive way building on the ideas of the Object-Oriented paradygm as improvements over sequential implementations of the same financial concepts. 

Moreover several [examples](https://github.com/gabrielepompa88/pyBlackScholesAnalytics/tree/master/examples) showcase the features of [**pyBlackScholesAnalytics**](https://github.com/gabrielepompa88/pyBlackScholesAnalytics) package and can be used as entry-point to begin the exploration of the package.

## Tutorials

|  | Jupyter Notebook | Youtube Video Playlist |
|:-------------------|:--------------------------:|:------------------:|
| **Derivatives Analytics - Introduction to Object Oriented Programming**: in this tutorial we introduce _Object-Oriented_ Programming in Python. We first make a non-financial example, developing the intuition behind the need of a change of programming paradigm to be able to cohordinate together different pieces of code. Once we have established the intuition, we then leverage on some basic financial knowledge to develop a Black-Scholes pricer for European call Options, first, and then a more general pricer for Plain-Vanilla put Options as well. | [:notebook:](https://github.com/gabrielepompa88/pyBlackScholesAnalytics/blob/master/Notebook_Tutorials/Derivatives_Analytics___Introduction_to_OOP.ipynb) | [:tv:]( https://www.youtube.com/playlist?list=PLRIS0g8TmV1NI7lr2I7BF9wdJ_PK9mVAz) |
| **Derivatives Analytics - Inheritance and Polymorphism**: in this tutorial we introduce _Inheritance_ and _Polymorphism_ in Python which are two milestones in Object-Oriented programming. We present these concepts introducing Digital cash-or-nothing Options and observing their similarities with Plain-Vanilla Options. Inheritance and Polymorphism allow us to leverage on the financial analogies between these two contracts and eventually represent them more efficiently as derived classes of a unique `EuropeanOption` abstract base class. | [:notebook:](https://github.com/gabrielepompa88/pyBlackScholesAnalytics/blob/master/Notebook_Tutorials/Derivatives_Analytics___Inheritance_and_Polymorphism.ipynb) | [:tv:]() |
| **Derivatives Analytics - Objects Composition**: in this tutorial we introduce _Composition_ which is an additional way to model relationships among objects, alternatively to Inheritance. We present this relationship introducing a common `MarketEnvironment` under which Option contracts are emitted, a `Portfolio` class is designed to aggregate Options and another `Plotter` class is designed to provide visualization routines. Finally, we examine several Option Strategies which uses the architecture implemented so far. | [:notebook:](https://github.com/gabrielepompa88/pyBlackScholesAnalytics/blob/master/Notebook_Tutorials/Derivatives_Analytics___Objects_Composition.ipynb) | [:tv:]() |
| **Derivatives Analytics - Options Greeks**: in this tutorial we introduce Option Greeks. That is, the derivatives of an option price with respect to its pricing parameters. We provide both a numeric computation using _finite-difference_ methods implemented in `NumericGreeks` class and their analytic expression using the Black-Scholes model. Finally, all features introduced in this and previous tutorial are collected in the `pyBlackScholesAnalytics` Python package which is hereby introduced. | [:notebook:](https://github.com/gabrielepompa88/pyBlackScholesAnalytics/blob/master/Notebook_Tutorials/Derivatives_Analytics___Options_Greeks.ipynb) | [:tv:]() |

## Examples

Ciao

# Contacts

This is still the first version of this package, so if you find errors, have comments or suggestions you can reach Gabriele Pompa (_gabriele.pompa@gmail.com_). If you wish to contribute, please contact me through [GitHub/gabrielepompa88](https://github.com/gabrielepompa88). If you are interested but feel a bit new to Python, I can recommend the open ["IT for Business and Finance"](https://github.com/gabrielepompa88/IT-For-Business-And-Finance-2019-20) as a reasonable starting point. 

Thank you in advance for your attention.
