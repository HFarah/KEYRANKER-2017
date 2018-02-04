========================
BUILD OUTPUT DESCRIPTION
========================

To run the project from the command line you must specify the following parameters go to the dist folder and
type the following:

rootDirectory : the path of the folder containing the data files (source.nt & target.nt) and the reference alignment file (refAlign.rdf).
typeOfResource : the type of resources to link.
depthOfRewriting : the depth of exploration for rewriting data.
sakey_n : the number of exceptions tolerated by Sakey.
minimumThreshold : minimum threshold to retain a similarity when comparing property values.
globalThreshold : global threshold to retain a similarity between key instantiations.
linkingTool : the used linking tool (Silk or Limes).
linkingToolThreshold : the comparison threshold used by the linking tool.
combineKeys : a boolean to select the combination of keys.

Important : the 'Executable' folder, containing the external applications, must be placed in the same location as 'KEYRANKER.jar'.
 
Command example :

java -jar "KEYRANKER.jar" "C:\KEYRANKER\Data\A_SPIMBENCH_small" "<http://www.bbc.co.uk/ontologies/creativework/BlogPost>" 2 1 1 1 silk 1 false



