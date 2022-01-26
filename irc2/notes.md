# Run
If in the folder irc2, this will run the container.
Might take a bit before the shell opens. When it does, run ``inspircd --runasroot`` (Ill change it to not need root later)
``$ irc2> docker run --rm -it $(docker build -q .)``

# Spawning From Image:
docker run dit <ID: fb86298823b5>