Dataset for each application is presented in data/app_name, where app_name can be nyx, iamr, or incflo.
nyx_hugepages4M contains the dataset used for Nyx3D ran with hugepages4M module loaded on Cori.
incflo/32 -- contains data for incflo that was run with input size = 32 x 32 x 32
Similarly, incflo/128 was run with n_cell = 128 x 128 x 128

app_name/groups/ folder contains hardware counter files that were collected on Cori.
app_name/jobs/ folder contains the raw data. app_name/jobs/00 contains hardware performance counters collected
for app_name/groups/*.00 file.
