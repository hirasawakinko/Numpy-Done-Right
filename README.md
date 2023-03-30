
Sup' man. Why is Rust so slow??


| Version                                                        | Avg time per iteration (ms)  | Multiplier | 
|----------------------------------------------------------------|------------------------------|------------|
| v1   - Baseline implementation (Python)                        | 340                          | 1x         |
| v1.5 - Numpy Done Wrong                                        | 46.5                         | 7.3x       |
| ~~v3 - `Polygon` implementation in Rust~~                      | ~~6.29~~                     | 46.53x     |
| ~~v4 - Optimized allocations~~                                 | ~~2.90~~                     | 101.16x    |
| [ver.Chika (**PURE Numpy**)](https://github.com/hirasawakinko/Numpy-Done-Right/blob/main/Numpy%20Done%20Right.ipynb)         | 0.973                        | 349.43X    |


## License

Refer to the original repository.
