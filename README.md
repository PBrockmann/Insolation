# Insolation

This software consists in three python libraries:
- astro.py is an interface (or computing code) to different astronomical solutions (Berger 1978, Laskar 2004,...) to provide the parameter needed to compute insolation: eccentricity, obliquity and climatic precession.
- inso.py (needs astro.py) computes several different flavors of "insolation": instantaneous, daily averaged or any other averaged insolation, "caloric seasons", ... useful for paleoclimatic or long-term climatic studies
- minmax_inso.py (needs astro.py and inso.py) computes extremal values of daily insolation.
