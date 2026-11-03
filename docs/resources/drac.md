# Digital Research Alliance of Canada (DRAC)

The Digital Research Alliance of Canada (DRAC), previously known as Compute Canada, is a national organization that provides advanced research computing (ARC) resources and services to Canadian researchers.

We typically use DRAC for analysis of public datasets. Specifically, we use the [nibi](https://www.alliancecan.ca/en/services/compute/nibi) cluster for our work.

### Getting Access to DRAC and nibi
1. Apply for a CCDB account: [Instructions](https://docs.alliancecan.ca/wiki/Apply_for_a_CCDB_account)
    - Kevin will need to approve your application, so please send him a message once you have submitted it. It may take a day or two for approval to be granted.
2. Once approved, login to the [CCDB portal](https://ccdb.alliancecan.ca/) and request access to the nibi cluster.
    - Select Resources -> HPC -> nibi and click "Request Access".

### Structure of Nibi Cluster
At a high level, the nibi cluster is structured as follows:

- **Projects**: Each lab has a project directory where all members can store and access data. For the Wang Lab, this is located at `/project/def-wanglab`.

- **Home Directories**: Each user has a home directory where they can store personal files. This is located at `/home/<username>`.

- **Scratch Directories**: Each user has a scratch directory for temporary storage of files. This is located at `/scratch/<username>`. Files in the scratch directory are not backed up and may be deleted after a certain period of time, so it is important to move any important files to your home or project directory.

### Learning more about DRAC and nibi
- [DRAC Documentation](https://docs.alliancecan.ca/wiki/Technical_documentation)
- [Nibi Documentation](https://docs.alliancecan.ca/wiki/Nibi)