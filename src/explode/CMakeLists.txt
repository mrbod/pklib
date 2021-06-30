buildAndPackageLib("explode"
	NON_RECURSIVE_GLOB
	COMPONENT "decompressor"
	DESCRIPTION "${PROJECT_DESCRIPTION}"
	PUBLIC_INCLUDES ${Include_dir}
	PRIVATE_LIBS "pkwareLUT"
)
pass_through_cpack_vars()
