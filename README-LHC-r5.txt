

This is a customized, R5 version of the "Smart on FHIR data generator" tool:
   https://github.com/smart-on-fhir/sample-patients-stu3

The original package produces STU3 resources and is no longer being mantained.

Important notes:
. This version can ONLY be used to produce R5 resources
. Must run in the bin/ directory
. Must specify --id-prefix (we use "smart")
. Must use python2 (e.g., 2.7)

==== To run it:
  cd bin;
  python2 generate.py --id-prefix smart --write-fhir <output-dir>(must exist)


