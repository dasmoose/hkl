AM_CFLAGS = -Wall -Wextra -Werror -Wno-unused-parameter -Wno-unused-function -std=gnu99
AM_LDFLAGS =
AM_YFLAGS = -d -v
AM_LFLAGS =

bin_PROGRAMS = hkl testbed

hkl_SOURCES = y.tab.y lex.yy.l hkl_string.c hkl_hash.c hkl_tree.c hkl.c \
hkl_deque.c hklr.c hklr_object.c hklr_expression.c hklr_statement.c \
hkl_value.c hkl_list.c hkl_variable.c hklr_function.c \
expression/hklr_op_size.c \
expression/hklr_op_typeof.c \
expression/hklr_op_minus.c \
expression/hklr_op_less.c \
expression/hklr_op_less_equal.c \
expression/hklr_op_greater.c \
expression/hklr_op_greater_equal.c \
expression/hklr_op_plus.c \
expression/hklr_op_multiply.c \
expression/hklr_op_divide.c \
expression/hklr_op_mod.c \
expression/hklr_op_not_equal.c \
expression/hklr_op_equal.c \
expression/hklr_op_coalesce.c \
expression/hklr_op_bitwise_or.c \
expression/hklr_op_bitwise_and.c \
expression/hklr_op_bitwise_xor.c \
expression/hklr_as_integer.c \
expression/hklr_as_real.c \
expression/hklr_as_string.c \
statement/hklr_statement_puts.c \
statement/hklr_statement_assign.c \
statement/hklr_statement_if.c \
statement/hklr_statement_while.c \
linenoise/linenoise.c

testbed_SOURCES = ${hkl_SOURCES}
testbed_SOURCES += test/traversal.c test/hash.c
