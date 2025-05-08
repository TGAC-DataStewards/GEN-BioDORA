# Upload data to AGH
The following repository will host all relevant documentation for workflows and metadata requirements for the upload of data to the AGH and  R2 platforms in the context of GEN-BioDORA.

All documentation about AGHub is located on this [repository](https://github.com/holstegelab/aghub_docs)

Simplified workflow for uploading data to AGH (without details):
1. **Register**: Register, setup your AGH account and request access to the AGHub. Details are here: [Getting_started](https://github.com/holstegelab/aghub_docs/blob/main/agh_getting_started.md)
2. **Set up ResearchDrive**: create RD account and link it to the AGHub. Details are here: [ResearchDrive](https://github.com/holstegelab/aghub_docs/blob/main/agh_use_of_research_drive.md) 
3. **Use rclone to upload data**: Upload raw data to RD. Raw data will be preprocessed by AGHub personeel (CRAM, ssVCF and pVCF will be created) 
 
> [!NOTE]
> 
> You have to provide tsv file with your data. More about tsv fileformat you can find here: [TSV and pipeline description](https://github.com/holstegelab/short_read_analyzing_pipeline_Snakemake/blob/main/README.md)

4. **Upload metadata**: Upload metadata to AGHub. 