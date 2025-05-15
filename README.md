# Insolation

This software consists in three python libraries:
- astro.py is an interface (or computing code) to different astronomical solutions (Berger 1978, Laskar 2004,...) to provide the parameters needed to compute insolation: eccentricity, obliquity and climatic precession. The reference one is Laskar 2004.
- inso.py (needs astro.py) computes several different flavors of "insolation": instantaneous, daily averaged or any other averaged insolation, "caloric seasons", ... useful for paleoclimatic or long-term climatic studies
- minmax_inso.py (needs astro.py and inso.py) computes extremal values of daily insolation.

Some example of use are also provided:
- figures.py generates some figures (for a paper to be submitted soon).
