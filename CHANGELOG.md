# Changes

## [Master]

### Added 

- Added converter for ``torch.Tensor.expand``
- Added support for custom converters for methods defined outside of ``torch`` module
- Added names for TensorRT layers
- Added GroupNorm plugin which internally uses PyTorch aten::group_norm
- Replaced Tensor.ndim references with len(tensor.shape) to support older pytorch versions
- Added reduced precision documentation page
- Added converters for ``floordiv``, ``mod``, ``ne``, and ``torch.tensor`` operations
- Extended ``relu`` converter to support ``Tensor.relu`` operation
- Extended ``sigmoid`` converter to support ``Tensor.sigmoid`` operation
