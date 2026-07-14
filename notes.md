# to myself

- While halfway through creation of the driver for the PS5169 I realized it was already on github. fml
  - still ended up finishing it, no idea what i'll do with it though.

# TODO

- [X] write retimer driver

dooone, just need to cover edge cases and optimize code. it works!

- [ ] check thermal sensors in dt

- [ ] check dp lanes

- [X] check reserved memory differences for bronco itself

The only two differences boil down to ADSP and video regions. I'll be skipping these because:
- These changes propagated from other devices (eqs in the case of bronco)
- **These algorithms will most likely never be used on mainline Linux.**
  - [Commit 1](https://github.com/LineageOS/android_kernel_motorola_sm8475-devicetrees/commit/d9faac9f62f0d281f6a5af68f46aea477af40cff.patch)
  - [Commit 2](https://github.com/LineageOS/android_kernel_motorola_sm8475-devicetrees/commit/e0ea65cad7cfbce13a2507315e34c7c4a4937776.patch)
  - [Commit 3](https://github.com/LineageOS/android_kernel_motorola_sm8475-devicetrees/commit/4011f03d7578f30d647515f37d06b8c969419a2d.patch)
  - [Commit 4](https://github.com/LineageOS/android_kernel_motorola_sm8475-devicetrees/commit/b44558ef74c42b6fa1352c7f839e21508b1582e0.patch)

- [ ] for added drivers, properly check dependencies

- [ ] rework nt37703 kconfig description
