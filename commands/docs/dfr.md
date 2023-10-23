---
title: dfr
categories: |
  dataframe
version: 0.86.0
dataframe: |
  Operate with data in a dataframe format.
usage: |
  Operate with data in a dataframe format.
---
<!-- This file is automatically generated. Please edit the command in https://github.com/nushell/nushell instead. -->

# <code>{{ $frontmatter.title }}</code> for dataframe

<div class='command-title'>{{ $frontmatter.dataframe }}</div>

## Signature

```> dfr {flags} ```


## Input/output types:

| input   | output |
| ------- | ------ |
| nothing | string |

## Notes
You must use one of the following subcommands. Using this command as-is will only produce this help message.

## Subcommands:

| name                                                           | type    | usage                                                                                            |
| -------------------------------------------------------------- | ------- | ------------------------------------------------------------------------------------------------ |
| [`dfr agg`](/commands/docs/dfr_agg.md)                         | Builtin | Performs a series of aggregations from a group-by.                                               |
| [`dfr agg-groups`](/commands/docs/dfr_agg-groups.md)           | Builtin | creates an agg_groups expression                                                                 |
| [`dfr all-false`](/commands/docs/dfr_all-false.md)             | Builtin | Returns true if all values are false.                                                            |
| [`dfr all-true`](/commands/docs/dfr_all-true.md)               | Builtin | Returns true if all values are true.                                                             |
| [`dfr append`](/commands/docs/dfr_append.md)                   | Builtin | Appends a new dataframe.                                                                         |
| [`dfr arg-max`](/commands/docs/dfr_arg-max.md)                 | Builtin | Return index for max value in series.                                                            |
| [`dfr arg-min`](/commands/docs/dfr_arg-min.md)                 | Builtin | Return index for min value in series.                                                            |
| [`dfr arg-sort`](/commands/docs/dfr_arg-sort.md)               | Builtin | Returns indexes for a sorted series.                                                             |
| [`dfr arg-true`](/commands/docs/dfr_arg-true.md)               | Builtin | Returns indexes where values are true.                                                           |
| [`dfr arg-unique`](/commands/docs/dfr_arg-unique.md)           | Builtin | Returns indexes for unique values.                                                               |
| [`dfr arg-where`](/commands/docs/dfr_arg-where.md)             | Builtin | Creates an expression that returns the arguments where expression is true.                       |
| [`dfr as`](/commands/docs/dfr_as.md)                           | Builtin | Creates an alias expression.                                                                     |
| [`dfr as-date`](/commands/docs/dfr_as-date.md)                 | Builtin | Converts string to date.                                                                         |
| [`dfr as-datetime`](/commands/docs/dfr_as-datetime.md)         | Builtin | Converts string to datetime.                                                                     |
| [`dfr cache`](/commands/docs/dfr_cache.md)                     | Builtin | Caches operations in a new LazyFrame                                                             |
| [`dfr col`](/commands/docs/dfr_col.md)                         | Builtin | Creates a named column expression.                                                               |
| [`dfr collect`](/commands/docs/dfr_collect.md)                 | Builtin | Collect lazy dataframe into eager dataframe.                                                     |
| [`dfr columns`](/commands/docs/dfr_columns.md)                 | Builtin | Show dataframe columns.                                                                          |
| [`dfr concat-str`](/commands/docs/dfr_concat-str.md)           | Builtin | Creates a concat string expression.                                                              |
| [`dfr concatenate`](/commands/docs/dfr_concatenate.md)         | Builtin | Concatenates strings with other array.                                                           |
| [`dfr contains`](/commands/docs/dfr_contains.md)               | Builtin | Checks if a pattern is contained in a string.                                                    |
| [`dfr count`](/commands/docs/dfr_count.md)                     | Builtin | creates a count expression                                                                       |
| [`dfr count-null`](/commands/docs/dfr_count-null.md)           | Builtin | Counts null values.                                                                              |
| [`dfr cumulative`](/commands/docs/dfr_cumulative.md)           | Builtin | Cumulative calculation for a series.                                                             |
| [`dfr datepart`](/commands/docs/dfr_datepart.md)               | Builtin | Creates an expression for capturing the specified datepart in a column.                          |
| [`dfr drop`](/commands/docs/dfr_drop.md)                       | Builtin | Creates a new dataframe by dropping the selected columns.                                        |
| [`dfr drop-duplicates`](/commands/docs/dfr_drop-duplicates.md) | Builtin | Drops duplicate values in dataframe.                                                             |
| [`dfr drop-nulls`](/commands/docs/dfr_drop-nulls.md)           | Builtin | Drops null values in dataframe.                                                                  |
| [`dfr dtypes`](/commands/docs/dfr_dtypes.md)                   | Builtin | Show dataframe data types.                                                                       |
| [`dfr dummies`](/commands/docs/dfr_dummies.md)                 | Builtin | Creates a new dataframe with dummy variables.                                                    |
| [`dfr explode`](/commands/docs/dfr_explode.md)                 | Builtin | Explodes a dataframe or creates a explode expression.                                            |
| [`dfr expr-not`](/commands/docs/dfr_expr-not.md)               | Builtin | creates a not expression                                                                         |
| [`dfr fetch`](/commands/docs/dfr_fetch.md)                     | Builtin | collects the lazyframe to the selected rows.                                                     |
| [`dfr fill-nan`](/commands/docs/dfr_fill-nan.md)               | Builtin | Replaces NaN values with the given expression.                                                   |
| [`dfr fill-null`](/commands/docs/dfr_fill-null.md)             | Builtin | Replaces NULL values with the given expression.                                                  |
| [`dfr filter`](/commands/docs/dfr_filter.md)                   | Builtin | Filter dataframe based in expression.                                                            |
| [`dfr filter-with`](/commands/docs/dfr_filter-with.md)         | Builtin | Filters dataframe using a mask or expression as reference.                                       |
| [`dfr first`](/commands/docs/dfr_first.md)                     | Builtin | Show only the first number of rows or create a first expression                                  |
| [`dfr flatten`](/commands/docs/dfr_flatten.md)                 | Builtin | An alias for dfr explode                                                                         |
| [`dfr get`](/commands/docs/dfr_get.md)                         | Builtin | Creates dataframe with the selected columns.                                                     |
| [`dfr get-day`](/commands/docs/dfr_get-day.md)                 | Builtin | Gets day from date.                                                                              |
| [`dfr get-hour`](/commands/docs/dfr_get-hour.md)               | Builtin | Gets hour from date.                                                                             |
| [`dfr get-minute`](/commands/docs/dfr_get-minute.md)           | Builtin | Gets minute from date.                                                                           |
| [`dfr get-month`](/commands/docs/dfr_get-month.md)             | Builtin | Gets month from date.                                                                            |
| [`dfr get-nanosecond`](/commands/docs/dfr_get-nanosecond.md)   | Builtin | Gets nanosecond from date.                                                                       |
| [`dfr get-ordinal`](/commands/docs/dfr_get-ordinal.md)         | Builtin | Gets ordinal from date.                                                                          |
| [`dfr get-second`](/commands/docs/dfr_get-second.md)           | Builtin | Gets second from date.                                                                           |
| [`dfr get-week`](/commands/docs/dfr_get-week.md)               | Builtin | Gets week from date.                                                                             |
| [`dfr get-weekday`](/commands/docs/dfr_get-weekday.md)         | Builtin | Gets weekday from date.                                                                          |
| [`dfr get-year`](/commands/docs/dfr_get-year.md)               | Builtin | Gets year from date.                                                                             |
| [`dfr group-by`](/commands/docs/dfr_group-by.md)               | Builtin | Creates a group-by object that can be used for other aggregations.                               |
| [`dfr implode`](/commands/docs/dfr_implode.md)                 | Builtin | Aggregates a group to a Series                                                                   |
| [`dfr into-df`](/commands/docs/dfr_into-df.md)                 | Builtin | Converts a list, table or record into a dataframe.                                               |
| [`dfr into-lazy`](/commands/docs/dfr_into-lazy.md)             | Builtin | Converts a dataframe into a lazy dataframe.                                                      |
| [`dfr into-nu`](/commands/docs/dfr_into-nu.md)                 | Builtin | Converts a dataframe or an expression into into nushell value for access and exploration.        |
| [`dfr is-duplicated`](/commands/docs/dfr_is-duplicated.md)     | Builtin | Creates mask indicating duplicated values.                                                       |
| [`dfr is-in`](/commands/docs/dfr_is-in.md)                     | Builtin | Creates an is-in expression.                                                                     |
| [`dfr is-not-null`](/commands/docs/dfr_is-not-null.md)         | Builtin | Creates mask where value is not null.                                                            |
| [`dfr is-null`](/commands/docs/dfr_is-null.md)                 | Builtin | Creates mask where value is null.                                                                |
| [`dfr is-unique`](/commands/docs/dfr_is-unique.md)             | Builtin | Creates mask indicating unique values.                                                           |
| [`dfr join`](/commands/docs/dfr_join.md)                       | Builtin | Joins a lazy frame with other lazy frame.                                                        |
| [`dfr last`](/commands/docs/dfr_last.md)                       | Builtin | Creates new dataframe with tail rows or creates a last expression.                               |
| [`dfr lit`](/commands/docs/dfr_lit.md)                         | Builtin | Creates a literal expression.                                                                    |
| [`dfr lowercase`](/commands/docs/dfr_lowercase.md)             | Builtin | Lowercase the strings in the column.                                                             |
| [`dfr ls`](/commands/docs/dfr_ls.md)                           | Builtin | Lists stored dataframes.                                                                         |
| [`dfr max`](/commands/docs/dfr_max.md)                         | Builtin | Creates a max expression or aggregates columns to their max value                                |
| [`dfr mean`](/commands/docs/dfr_mean.md)                       | Builtin | Creates a mean expression for an aggregation or aggregates columns to their mean value           |
| [`dfr median`](/commands/docs/dfr_median.md)                   | Builtin | Aggregates columns to their median value                                                         |
| [`dfr melt`](/commands/docs/dfr_melt.md)                       | Builtin | Unpivot a DataFrame from wide to long format.                                                    |
| [`dfr min`](/commands/docs/dfr_min.md)                         | Builtin | Creates a min expression or aggregates columns to their min value                                |
| [`dfr n-unique`](/commands/docs/dfr_n-unique.md)               | Builtin | Counts unique values.                                                                            |
| [`dfr not`](/commands/docs/dfr_not.md)                         | Builtin | Inverts boolean mask.                                                                            |
| [`dfr open`](/commands/docs/dfr_open.md)                       | Builtin | Opens CSV, JSON, JSON lines, arrow, avro, or parquet file to create dataframe.                   |
| [`dfr otherwise`](/commands/docs/dfr_otherwise.md)             | Builtin | completes a when expression.                                                                     |
| [`dfr quantile`](/commands/docs/dfr_quantile.md)               | Builtin | Aggregates the columns to the selected quantile.                                                 |
| [`dfr query`](/commands/docs/dfr_query.md)                     | Builtin | Query dataframe using SQL. Note: The dataframe is always named 'df' in your query's from clause. |
| [`dfr rename`](/commands/docs/dfr_rename.md)                   | Builtin | Rename a dataframe column.                                                                       |
| [`dfr replace`](/commands/docs/dfr_replace.md)                 | Builtin | Replace the leftmost (sub)string by a regex pattern.                                             |
| [`dfr replace-all`](/commands/docs/dfr_replace-all.md)         | Builtin | Replace all (sub)strings by a regex pattern.                                                     |
| [`dfr reverse`](/commands/docs/dfr_reverse.md)                 | Builtin | Reverses the LazyFrame                                                                           |
| [`dfr rolling`](/commands/docs/dfr_rolling.md)                 | Builtin | Rolling calculation for a series.                                                                |
| [`dfr sample`](/commands/docs/dfr_sample.md)                   | Builtin | Create sample dataframe.                                                                         |
| [`dfr select`](/commands/docs/dfr_select.md)                   | Builtin | Selects columns from lazyframe.                                                                  |
| [`dfr set`](/commands/docs/dfr_set.md)                         | Builtin | Sets value where given mask is true.                                                             |
| [`dfr set-with-idx`](/commands/docs/dfr_set-with-idx.md)       | Builtin | Sets value in the given index.                                                                   |
| [`dfr shape`](/commands/docs/dfr_shape.md)                     | Builtin | Shows column and row size for a dataframe.                                                       |
| [`dfr shift`](/commands/docs/dfr_shift.md)                     | Builtin | Shifts the values by a given period.                                                             |
| [`dfr slice`](/commands/docs/dfr_slice.md)                     | Builtin | Creates new dataframe from a slice of rows.                                                      |
| [`dfr sort-by`](/commands/docs/dfr_sort-by.md)                 | Builtin | sorts a lazy dataframe based on expression(s).                                                   |
| [`dfr std`](/commands/docs/dfr_std.md)                         | Builtin | Creates a std expression for an aggregation of std value from columns in a dataframe             |
| [`dfr str-lengths`](/commands/docs/dfr_str-lengths.md)         | Builtin | Get lengths of all strings.                                                                      |
| [`dfr str-slice`](/commands/docs/dfr_str-slice.md)             | Builtin | Slices the string from the start position until the selected length.                             |
| [`dfr strftime`](/commands/docs/dfr_strftime.md)               | Builtin | Formats date based on string rule.                                                               |
| [`dfr sum`](/commands/docs/dfr_sum.md)                         | Builtin | Creates a sum expression for an aggregation or aggregates columns to their sum value             |
| [`dfr summary`](/commands/docs/dfr_summary.md)                 | Builtin | For a dataframe, produces descriptive statistics (summary statistics) for its numeric columns.   |
| [`dfr take`](/commands/docs/dfr_take.md)                       | Builtin | Creates new dataframe using the given indices.                                                   |
| [`dfr to-arrow`](/commands/docs/dfr_to-arrow.md)               | Builtin | Saves dataframe to arrow file.                                                                   |
| [`dfr to-avro`](/commands/docs/dfr_to-avro.md)                 | Builtin | Saves dataframe to avro file.                                                                    |
| [`dfr to-csv`](/commands/docs/dfr_to-csv.md)                   | Builtin | Saves dataframe to CSV file.                                                                     |
| [`dfr to-jsonl`](/commands/docs/dfr_to-jsonl.md)               | Builtin | Saves dataframe to a JSON lines file.                                                            |
| [`dfr to-parquet`](/commands/docs/dfr_to-parquet.md)           | Builtin | Saves dataframe to parquet file.                                                                 |
| [`dfr unique`](/commands/docs/dfr_unique.md)                   | Builtin | Returns unique values from a dataframe.                                                          |
| [`dfr uppercase`](/commands/docs/dfr_uppercase.md)             | Builtin | Uppercase the strings in the column.                                                             |
| [`dfr value-counts`](/commands/docs/dfr_value-counts.md)       | Builtin | Returns a dataframe with the counts for unique values in series.                                 |
| [`dfr var`](/commands/docs/dfr_var.md)                         | Builtin | Create a var expression for an aggregation                                                       |
| [`dfr when`](/commands/docs/dfr_when.md)                       | Builtin | Creates and modifies a when expression.                                                          |
| [`dfr with-column`](/commands/docs/dfr_with-column.md)         | Builtin | Adds a series to the dataframe.                                                                  |

**Tips:** Dataframe commands were not shipped in the official binaries by default, you have to build it with `--features=dataframe` flag