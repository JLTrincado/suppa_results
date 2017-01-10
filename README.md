###To run diffSplice

`for file in ./*; do gunzip "$file"; done`

`python suppa.py diffSplice -m empirical -i annotation/hg19_refseq_all_events.ioe -e CTRL.tpm KD.tpm -p CTRL.psi KD.psi -o CTRL_KD`
