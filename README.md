```sh
$ npm i
npm WARN pack-test@1.0.0 No description
npm WARN pack-test@1.0.0 No repository field.

added 1 package and audited 1943 packages in 1.492s
found 0 vulnerabilities

$ pack build
@pika/pack build v0.3.1
[1/5] Validating source...
[2/5] Preparing pipeline...
      ❇️  pkg/
[3/5] Running @pika/plugin-standard-pkg...
      📝  pkg/dist-src/index.js [esnext]
      » Linting with standard-pkg...
[4/5] Running @pika/plugin-build-node...
Error: "dist-src/" does not exist, or was not yet created in the pipeline.
```