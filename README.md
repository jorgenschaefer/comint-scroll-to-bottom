This will cause comint buffers to always display the maximum amount of
output by keeping the prompt at the bottom of the respective window.
The code is taken from ERC, and adapted to comint-mode.

This also uses `window-scroll-functions`, which is not exactly
intended for this use, but there is currently no better solution.
