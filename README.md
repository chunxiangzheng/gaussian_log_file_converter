# gaussian_log_file_converter
Convert Gaussian optimization output (.log) file to xyz or gjf file
Usage: python extractOptimizedCoords.py input.log xyz|gjf

If the optimization finished successfully, the output file name will be input_optimized_out.[xyz|gjf]
Otherwise, the output file name will be input_out.[xyz|gjf].  The coordinates for the lowest energy structure will be used in the output file.

Sample input:
snap_11.log (Optimization failed)
snap_25.log (Optimization succeeded)
