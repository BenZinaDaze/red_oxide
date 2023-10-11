# 0.7.0 (2023-10-11)


### Bug Fixes

* Flac24 -> Flac do not need tags copied ([0264471](https://github.com/BenZinaDaze/red_oxide/commit/02644717f10f507d8da5421b59675b81f57a2db0))
* **group_name:** make sure group names do not have colons in name ([e18b95b](https://github.com/BenZinaDaze/red_oxide/commit/e18b95b89864de0671ebd1533aefc7c692769890))
* **imdl:** set correct source for RED ([39bb591](https://github.com/BenZinaDaze/red_oxide/commit/39bb591a1addf440a0fa3f2d47f9480160fe494a))
* **path:** correctly parse reds file_path property for utf-8 chars ([342d6dc](https://github.com/BenZinaDaze/red_oxide/commit/342d6dc1788681fe681acd9b80b48aaab4b2f73d))
* **permalink:** properly handle error when permalink can't be parsed ([d92aa0b](https://github.com/BenZinaDaze/red_oxide/commit/d92aa0b40598d418cb41ad9c3e355d21ec4fd7f2))
* **redacted:** check if files exceed redacteds allowed path limit ([020afab](https://github.com/BenZinaDaze/red_oxide/commit/020afabfda15655c00f6dee6b869fc1b0f65c593))
* **redacted:** correct Blu-ray -> Blu-Ray for api response ([aa72cb1](https://github.com/BenZinaDaze/red_oxide/commit/aa72cb12604ee01a128c69f26f7056108791062e))
* **red:** fix TRACKER_URL having an extra slash ([142db81](https://github.com/BenZinaDaze/red_oxide/commit/142db819adb64ad7873a339b93e2cb8c5de5a16e))
* **spectrograms:** correct error message ([18035b4](https://github.com/BenZinaDaze/red_oxide/commit/18035b48d3b6f48c13b4e1a6b0ca425be7b4e449))
* **spectrograms:** skip upload when spectrogram check is negative ([ad3198d](https://github.com/BenZinaDaze/red_oxide/commit/ad3198d96789141fa3764dda615d2040da96c00e))
* **tags:** correctly check subfolders for flac files ([678d071](https://github.com/BenZinaDaze/red_oxide/commit/678d071dc89364664462997e51dc9a23c154a5f5))
* **tags:** correctly copy tags for FLAC24 -> FLAC transcodes ([929a0c0](https://github.com/BenZinaDaze/red_oxide/commit/929a0c07cf55075d2a228491f2d76a3de4c2d956))
* **tags:** correctly handle vinyl edge cases for track_number tags ([b53f16d](https://github.com/BenZinaDaze/red_oxide/commit/b53f16d32447b2abea5091f7d381ad050c369979))
* **transcode:** correct display command for FLAC24 -> FLAC ([adf0fab](https://github.com/BenZinaDaze/red_oxide/commit/adf0fab4325c59f83cfecf7978bdaef5052fe17c))
* **transcode:** correct use .flac file extension for FLAC24 -> FLAC ([080dab7](https://github.com/BenZinaDaze/red_oxide/commit/080dab78e0a848852d4f0a97426837c27d409e10))
* **transcode:** fix path in recursion while copying over extra files ([74ab6e2](https://github.com/BenZinaDaze/red_oxide/commit/74ab6e2f7d1aaa6e7e5860e480475a65cfe2f908))
* **upload:** correctly implement auto upload ([9b24231](https://github.com/BenZinaDaze/red_oxide/commit/9b24231b9363e882f86e3cda5981d3e6d4afa92a))


### Features

* add concurrency option to specify how many tasks should run concurrently ([baee787](https://github.com/BenZinaDaze/red_oxide/commit/baee787e820a50229a24d89fff5381a0db8ec344))
* add skip_existing_formats_check flag ([6a7bae8](https://github.com/BenZinaDaze/red_oxide/commit/6a7bae8690461274eb02f759ab69471adb08b25c))
* add way to set allowed transcode targets in cli & via the config ([90d2b02](https://github.com/BenZinaDaze/red_oxide/commit/90d2b0261345ab3fcb8d7c439419272f3d86a7c3))
* **cli:** add short alias for move_transcode_to_content ([77722ef](https://github.com/BenZinaDaze/red_oxide/commit/77722ef6be62e4831acbd87afbf745682ddcdb10))
* **config:** add missing options and flags to configmake & optional ([e23dba0](https://github.com/BenZinaDaze/red_oxide/commit/e23dba042d8b2d0cbe4ab6f318897bd38db19009))
* don't fail on errors, replace forbidden folder/filename characters ([44b3486](https://github.com/BenZinaDaze/red_oxide/commit/44b3486738a590ff1b7b5cec18a7b607d1fbc222))
* implement manual mode ([4be871c](https://github.com/BenZinaDaze/red_oxide/commit/4be871c0652303535725eb3c77c12d764db22637))
* initial upload functionality ([dce3008](https://github.com/BenZinaDaze/red_oxide/commit/dce30083d50b0ffd11eb3ada54d8fd9bf87df43f))
* **redacted:** add version to upload description ([3b56f9d](https://github.com/BenZinaDaze/red_oxide/commit/3b56f9d0e4dd48346bacf4bc80b201bf78715711))
* **spectrogram:** add progress bar for spectrogram creation ([386682d](https://github.com/BenZinaDaze/red_oxide/commit/386682d17ebd192aa7d4905fdd9720834a89c62e))
* **spectrograms:** add filename info ([76892f5](https://github.com/BenZinaDaze/red_oxide/commit/76892f5916dda0007de7463d0891700e7ad87c8e))
* **spectrograms:** add spectrogram creation and let users manually check ([34aad94](https://github.com/BenZinaDaze/red_oxide/commit/34aad9428789c91a02a30be5c8e9c287fbe6d419))
* **threads:** remove useless threads argument ([9cc7be8](https://github.com/BenZinaDaze/red_oxide/commit/9cc7be8c937493f92092cfa26e28b872242388b8))
* **transcode:** add total progress bar, fix ghost bar showing up ([ba947c0](https://github.com/BenZinaDaze/red_oxide/commit/ba947c0614e5cd161b3f70174e0c43ccea142074))
* **upload:** add log message once upload is done ([5521e25](https://github.com/BenZinaDaze/red_oxide/commit/5521e25d65942816ca9f423c160298c216bfb940))


### Performance Improvements

* **main:** remove double multichannel check ([44e0df3](https://github.com/BenZinaDaze/red_oxide/commit/44e0df3b045e5797509f90c02867b4057d230a09))
* **spectrograms:** add support for concurrency option ([1ecf337](https://github.com/BenZinaDaze/red_oxide/commit/1ecf3377fa4fda9808e103adb5daa34361917e48))



