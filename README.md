libpsimd for Unikraft
===================
This is our initial port of psimd to Unikraft as an external library.
The intel-intrinsics library is required. When adding the
library to the dependency list, psimd should stay after
intel-intrinsics, e.g.,:

	    ... :$(UK_LIBS)/intel-intrinsics:$(UK_LIBS)/psimd: ...
				
For more information, please refer to the `README.md` as well as the
documentation in the `doc/` subdirectory of the main unikraft
repository.
