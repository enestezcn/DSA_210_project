# DSA 210 project

# Song Genre Transition Analysis
The goal of this project is to explore how I transition between song genres during my Spotify listening sessions. By identifying and analyzing these transitions, I aim to uncover patterns in my listening habits and understand which genres are most connected in my personal music preferences. 

# Data Collection and Preparation
I will collect using the Spotify API, which provides metadata for tracks, including genres.
songs will devide into broad categories like Rap, Blues, Pop, and Jazz because spotify genres devided litte narrow. 
Tracking the listening history ı am going to identify consecutive genre transitions.

# Analysis
I am going to analysis the frequency of transitions between genres.
Transitions like "Rap → Blues" and "Blues → Jazz" were found to be the most common.
These transitions were visualized using a directed graph, where nodes represent genres and arrows represent transitions, with the thickness of arrows indicating frequency.

# Findings
- Dominant Transitions: The most frequent genre switches.
- Genre Relationships: Certain genres, like Blues, act as "bridges" between others, often connecting Rap and Jazz. 


# Visualizations
ı will create a network graph to show genre relationships. Nodes represent genres, and arrows show the transitions, with their size proportional to frequency there might be more than one connection accorging to relationship between genres. For example "rap -> blues", "rap -> jazz" and ı will going to show these graph connecting one genre to another respective to their frequency.  
