---
title: Jan 8, 2015 - Number Theory
layout: article
category: meetings
excerpt: NOTE, Change of venue! Dana Jacobsen will give a talk on his number theory module. This is an early version of the talk for FOSDEM.
---

----

### Change of Venue

**
We're going to change things up this month and will be hosting our first
meeting of the year downtown.
Join us at the [Portland Incubator Experiment (PIE) office][piepdx],
located at 12th and NW Davis.
PIE is next to the streetcar, walking distance from the MAX,
and Brewery Parking Garage is across the street if you are driving.
**

[piepdx]: http://calagator.org/venues/202391901

----

Dana Jacobsen will give a talk on his number theory module. This is an early
version of the talk for [FOSDEM][fosdem].

This talk describes the history, design, and implementation details of a number
theory module for Perl. With implementations for most functions in C, C+GMP,
and Perl this offers speed on most platforms as well as portability.
Comparisons will be made with tools such as Pari/GP, SymPy, SAGE, Primo,
OpenPFGW, and others.

The Perl ntheory module (aka Math::Prime::Util) offers a portable solution for
many integer number theory tasks in Perl. While not offering the full feature
set of robust and mature packages such as Pari/GP and SAGE, there are many
areas where this package offers improvements.

With implementations in C, C+GMP, and Perl, there were a number of design
choices made. We describe the choices and tradeoffs of making a package that is
both portable, robust, and performant. Design choices for some algorithms (e.g.
primality tests) are also discussed.

Highlights of this open source package include:

 *  Fastest single threaded open source prime count and nthprime
 *  Fastest 64-bit primality testing
 *  Fastest bigint probable prime testing to 10k digits
 *  Fastest nextprime, prev_prime
 *  Fastest open source AKS primality proofs
 *  Fastest open source ECPP primality proofs
 *  Support for random primes and random proven primes
 *  Ability to compile standalone C programs for tasks such as prime count,
    primality tests, primality proving, and primality certificate verification.

The random primes and primality testing/proving have been used in some new
crypto modules, replacing older CPAN modules that were slower and had defects.
The ECPP verifier written as part of this project is being used by FactorDB. In
less than a year of use, simple Perl scripts using this module have been able
to find over 47% of all current record prime gaps. Numerous defects in other
open source packages have been identified during testing of this module.

[fosdem]: https://fosdem.org/2015/
