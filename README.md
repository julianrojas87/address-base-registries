# 🇪🇺 Address Base Registries in the EU 🇪🇺

RML mappings to transform (some of) the EU address base registry data dumps to RDF following the [EU Core Location vocabulary](https://semiceu.github.io/Core-Location-Vocabulary/releases/2.0.1/).

Each folder contains an RML mapping file and instructions on how to access the official data dump of each member state.
The data can be transformed using the [RMLStreamer engine](https://github.com/RMLio/RMLStreamer/releases/download/v2.4.2/RMLStreamer-2.4.2-standalone.jar) with the following command:

```bash
java -jar RMLStreamer-2.4.2-standalone.jar toFile -m <replace_with_mapping_file> -o </path/to/desired/output/folder> 
```
