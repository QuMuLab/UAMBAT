Universal Adapter Mechanism for Bridging Action Theories (UAMBAT)
=================================================================

This project aims to serve as mechanism for converting between various action
theory formalisms. Possible uses include, but are not limited to,

1. Translation between the supported formalisms (e.g., GDL <-> PDDL)
2. Analysis / simplification of actions (e.g., adding or removing preconditions and effects)
3. Combining formalisms (e.g., mixing GDL and SitCalc for solving with planners)
4. Analysis in target languages (e.g., convert to PDDL, use planner preprocess, then convert back)
5. Visualizing the semantic interpretation of a proposed action schema (e.g., cool figures!)

The project is currently in its inception phase, and if you would like to be
involved at any level (from active collaboration to just cheering us on), then
contact [Christian Muise](http://www.haz.ca/) for more information.

----------------------

The project is broken down into the following directories:

* **adapters**: Code for the various centralized representation languages (e.g., d-DNNF)
* **endpoints**: Code for the various input languages (e.g., PDDL, GDL, SitCalc, etc)
* **examples**: Various example files we use to test the systems.
