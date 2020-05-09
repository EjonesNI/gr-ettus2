# gr-ettus: Experimental UHD and USRP features for GNU Radio

This is an out-of-tree module with experimental and other features
extending gr-uhd.

For regular USRP operations, this OOT module is *not* required.

## Dependencies

This OOT requires GNU Radio version 3.8.0 with gr-uhd enabled.
It also requires the UHD 3.15-LTS to be installed.

You will also need to install the fosphor OOT module found here: https://github.com/osmocom/gr-fosphor, which requires the following be installed/executed beforehand: sudo apt install ocl-icd-opencl-dev

## RFNoC

Currently, this OOT is required to run RFNoC with GNU Radio.

## License

All code in this repository is licensed under the GPLv3 (see file
COPYING). Unless stated otherwise, copyright belongs to Ettus Research.

In some cases, copyright may already have been transferred to the FSF
for blocks that are planned for inclusion in gr-uhd.
