# sketch-collaboration
A repo to test design+code collaboration with Sketch.

# Scripts for push and pull

upload.sh
1. Pull the latest changes from the repo
2. Copy .sketch to .zip
3. Extract the core `.sketch` data from the .zip and deletes it
4. Remove the preview image (only full size images will be added to the index)
5. Add the core data to the git index
6. Commit and pushes the data

download.sh
1. Pull the latest changes from the repo
2. Zip the core Sketch data
3. Copy .zip to .sketch and delete .zip
