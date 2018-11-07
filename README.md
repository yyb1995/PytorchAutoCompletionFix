# PytorchAutoCompletionFix
This is a fix file for Pytorch autocompletion in Pycharm. 
While using Pytorch in Pycharm, I encounter the problem that Pycharm doesn't give completion hint on some Pytorch built-in function such as torch.empty() and torch.rand(). I google it and find a good solution.
## Usage
Put `__init__.pyi` into pytorch installation location. For me it's `~/.local/lib/python3.6/site-packages/torch`. Then you will see that code completion hint come back! Many thanks to the author **t-vi**!
## Reference
1. [https://gist.github.com/t-vi/0d0ae013072f96f50fa11fbc2287e33b](https://gist.github.com/t-vi/0d0ae013072f96f50fa11fbc2287e33b)
