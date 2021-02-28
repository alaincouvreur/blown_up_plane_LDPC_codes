# blown_up_plane_LDPC_codes
Author : Alain Couvreur
contact : alain.couvreur@inria.fr

This is a Magma program to construct the LDPC codes
designed in the article:
Alain Couvreur. Incidence Structures From the Blown up Plane and LDPC Codes.
IEEE Trans. Inform. Theory. 57(7), 4401-4416. 2011.
----------------------------------

Copy the files in your current folder and start MAGMA.
To construct codes of type C1 (resp. C2, C3) do

> load "C1_codes.mgm";

(resp. C2_codes.mgm C3_codes.mgm)

Then you get the parity-check matrix of the
code arising from the plane over F_q with the command:

> C1code(q);

CAUTION: It is a sparse representation of the matrix!

Have fun!!
