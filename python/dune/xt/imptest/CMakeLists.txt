# ~~~
# This file is part of the dune-xt-common project:
#   https://github.com/dune-community/dune-xt-common
# Copyright 2009-2018 dune-xt-common developers and contributors. All rights reserved.
# License: Dual licensed as BSD 2-Clause License (http://opensource.org/licenses/BSD-2-Clause)
#      or  GPL-2.0+ (http://opensource.org/licenses/gpl-license)
#          with "runtime exception" (http://www.dune-project.org/license.html)
# Authors:
#   René Fritze (2018)
# ~~~


dune_pybindxi_add_module(_first EXCLUDE_FROM_ALL first.cc)
dune_pybindxi_add_module(_second EXCLUDE_FROM_ALL second.cc)
dune_pybindxi_add_module(_third EXCLUDE_FROM_ALL third.cc)
