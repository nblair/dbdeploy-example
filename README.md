## dbdeploy-example

Example using dbdeploy Maven plugin.

### Running

Create the schema (TODO is there a better lifecycle phase?):

    mvn package

Run the deltas:

	mvn dbdeploy:update


