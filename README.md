# HW2_Madrazo
Applied Bioinformatics Course


for file in ./data/fastq/*.fq
do
  cp -r ./data/fastq/*.fq ./data/new_folder/
done

cd ./data/new_folder/*.fq
mv "${file}" "${file/.fq/.fastq}"
