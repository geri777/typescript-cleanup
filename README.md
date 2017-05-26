This is a fork of https://github.com/alphazygma/typescript-cleanup
# typescript-cleanup
Small NodeJs script to help cleanup compiled JS/MAP files

This fork adds the following feature(s):
- find orphaned .js/.map files (=not having a .ts file)
- ignore orphaned files if they are named \*.min.map (which might be mapping between compressed/uncompressed)
