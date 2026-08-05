# kolpri145-cpu.github.io
{
  "name": "clickerbot.local",
  "version": "1.0.0",
  "lockfileVersion": 3,
  "requires": true,
  "packages": {
    "": {
      "name": "clickerbot.local",
      "version": "1.0.0",
      "license": "ISC",
      "dependencies": {
        "@rollup/plugin-terser": "^0.4.4",
        "axios": "^1.7.2",
        "bcrypt": "^5.1.1",
        "date-fns": "^3.6.0",
        "dotenv": "^16.4.5",
        "express": "^4.19.2",
        "helmet": "^7.1.0",
        "jsonwebtoken": "^9.0.2",
        "md5": "^2.3.0",
        "mysql2": "^3.10.0",
        "node-telegram-bot-api": "^0.66.0",
        "nodemailer": "^6.9.13",
        "sequelize": "^6.37.3",
        "socket.io": "^4.7.5",
        "svelte": "^4.2.18",
        "svelte-chartjs": "^3.1.5",
        "svelte-i18n": "^4.0.0",
        "svelte-routing": "^2.13.0",
        "svelte-toast": "^1.0.0",
        "trello-node-api": "^0.0.9"
      },
      "devDependencies": {
        "@rollup/plugin-commonjs": "^26.0.1",
        "@rollup/plugin-node-resolve": "^13.3.0",
        "nodemon": "^3.1.3",
        "rollup": "^2.79.1",
        "rollup-plugin-css-only": "^4.5.2",
        "rollup-plugin-livereload": "^2.0.5",
        "rollup-plugin-svelte": "^7.2.2",
        "rollup-plugin-terser": "^7.0.2",
        "sirv-cli": "^2.0.0",
        "supertest": "^7.0.0",
        "svelte-preprocess": "^5.1.4"
      }
    },
    "node_modules/@ampproject/remapping": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/@ampproject/remapping/-/remapping-2.3.0.tgz",
      "integrity": "sha512-30iZtAPgz+LTIYoeivqYo853f02jBYSd5uGnGpkFV0M3xOt9aN73erkgYAmZU43x4VfqcnLxW9Kpg3R5LC4YYw==",
      "dependencies": {
        "@jridgewell/gen-mapping": "^0.3.5",
        "@jridgewell/trace-mapping": "^0.3.24"
      },
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/@babel/code-frame": {
      "version": "7.24.7",
      "resolved": "https://registry.npmjs.org/@babel/code-frame/-/code-frame-7.24.7.tgz",
      "integrity": "sha512-BcYH1CVJBO9tvyIZ2jVeXgSIMvGZ2FDRvDdOIVQyuklNKSsx+eppDEBq/g47Ayw+RqNFE+URvOShmf+f/qwAlA==",
      "dev": true,
      "dependencies": {
        "@babel/highlight": "^7.24.7",
        "picocolors": "^1.0.0"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-validator-identifier": {
      "version": "7.24.7",
      "resolved": "https://registry.npmjs.org/@babel/helper-validator-identifier/-/helper-validator-identifier-7.24.7.tgz",
      "integrity": "sha512-rR+PBcQ1SMQDDyF6X0wxtG8QyLCgUB0eRAGguqRLfkCA87l7yAP7ehq8SNj96OOGTO8OBV70KhuFYcIkHXOg0w==",
      "dev": true,
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/highlight": {
      "version": "7.24.7",
      "resolved": "https://registry.npmjs.org/@babel/highlight/-/highlight-7.24.7.tgz",
      "integrity": "sha512-EStJpq4OuY8xYfhGVXngigBJRWxftKX9ksiGDnmlY3o7B/V7KIAc9X4oiK87uPJSc/vs5L869bem5fhZa8caZw==",
      "dev": true,
      "dependencies": {
        "@babel/helper-validator-identifier": "^7.24.7",
        "chalk": "^2.4.2",
        "js-tokens": "^4.0.0",
        "picocolors": "^1.0.0"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@cypress/request": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/@cypress/request/-/request-3.0.1.tgz",
      "integrity": "sha512-TWivJlJi8ZDx2wGOw1dbLuHJKUYX7bWySw377nlnGOW3hP9/MUKIsEdXT/YngWxVdgNCHRBmFlBipE+5/2ZZlQ==",
      "dependencies": {
        "aws-sign2": "~0.7.0",
        "aws4": "^1.8.0",
        "caseless": "~0.12.0",
        "combined-stream": "~1.0.6",
        "extend": "~3.0.2",
        "forever-agent": "~0.6.1",
        "form-data": "~2.3.2",
        "http-signature": "~1.3.6",
        "is-typedarray": "~1.0.0",
        "isstream": "~0.1.2",
        "json-stringify-safe": "~5.0.1",
        "mime-types": "~2.1.19",
        "performance-now": "^2.1.0",
        "qs": "6.10.4",
        "safe-buffer": "^5.1.2",
        "tough-cookie": "^4.1.3",
        "tunnel-agent": "^0.6.0",
        "uuid": "^8.3.2"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/@cypress/request-promise": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/@cypress/request-promise/-/request-promise-5.0.0.tgz",
      "integrity": "sha512-eKdYVpa9cBEw2kTBlHeu1PP16Blwtum6QHg/u9s/MoHkZfuo1pRGka1VlUHXF5kdew82BvOJVVGk0x8X0nbp+w==",
      "dependencies": {
        "bluebird": "^3.5.0",
        "request-promise-core": "1.1.3",
        "stealthy-require": "^1.1.1",
        "tough-cookie": "^4.1.3"
      },
      "engines": {
        "node": ">=0.10.0"
      },
      "peerDependencies": {
        "@cypress/request": "^3.0.0"
      }
    },
    "node_modules/@cypress/request/node_modules/form-data": {
      "version": "2.3.3",
      "resolved": "https://registry.npmjs.org/form-data/-/form-data-2.3.3.tgz",
      "integrity": "sha512-1lLKB2Mu3aGP1Q/2eCOx0fNbRMe7XdwktwOruhfqqd0rIJWwN4Dh+E3hrPSlDCXnSR7UtZ1N38rVXm+6+MEhJQ==",
      "dependencies": {
        "asynckit": "^0.4.0",
        "combined-stream": "^1.0.6",
        "mime-types": "^2.1.12"
      },
      "engines": {
        "node": ">= 0.12"
      }
    },
    "node_modules/@cypress/request/node_modules/qs": {
      "version": "6.10.4",
      "resolved": "https://registry.npmjs.org/qs/-/qs-6.10.4.tgz",
      "integrity": "sha512-OQiU+C+Ds5qiH91qh/mg0w+8nwQuLjM4F4M/PbmhDOoYehPh+Fb0bDjtR1sOvy7YKxvj28Y/M0PhP5uVX0kB+g==",
      "dependencies": {
        "side-channel": "^1.0.4"
      },
      "engines": {
        "node": ">=0.6"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/@esbuild/aix-ppc64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/aix-ppc64/-/aix-ppc64-0.19.12.tgz",
      "integrity": "sha512-bmoCYyWdEL3wDQIVbcyzRyeKLgk2WtWLTWz1ZIAZF/EGbNOwSA6ew3PftJ1PqMiOOGu0OyFMzG53L0zqIpPeNA==",
      "cpu": [
        "ppc64"
      ],
      "optional": true,
      "os": [
        "aix"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/android-arm": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/android-arm/-/android-arm-0.19.12.tgz",
      "integrity": "sha512-qg/Lj1mu3CdQlDEEiWrlC4eaPZ1KztwGJ9B6J+/6G+/4ewxJg7gqj8eVYWvao1bXrqGiW2rsBZFSX3q2lcW05w==",
      "cpu": [
        "arm"
      ],
      "optional": true,
      "os": [
        "android"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/android-arm64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/android-arm64/-/android-arm64-0.19.12.tgz",
      "integrity": "sha512-P0UVNGIienjZv3f5zq0DP3Nt2IE/3plFzuaS96vihvD0Hd6H/q4WXUGpCxD/E8YrSXfNyRPbpTq+T8ZQioSuPA==",
      "cpu": [
        "arm64"
      ],
      "optional": true,
      "os": [
        "android"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/android-x64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/android-x64/-/android-x64-0.19.12.tgz",
      "integrity": "sha512-3k7ZoUW6Q6YqhdhIaq/WZ7HwBpnFBlW905Fa4s4qWJyiNOgT1dOqDiVAQFwBH7gBRZr17gLrlFCRzF6jFh7Kew==",
      "cpu": [
        "x64"
      ],
      "optional": true,
      "os": [
        "android"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/darwin-arm64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/darwin-arm64/-/darwin-arm64-0.19.12.tgz",
      "integrity": "sha512-B6IeSgZgtEzGC42jsI+YYu9Z3HKRxp8ZT3cqhvliEHovq8HSX2YX8lNocDn79gCKJXOSaEot9MVYky7AKjCs8g==",
      "cpu": [
        "arm64"
      ],
      "optional": true,
      "os": [
        "darwin"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/darwin-x64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/darwin-x64/-/darwin-x64-0.19.12.tgz",
      "integrity": "sha512-hKoVkKzFiToTgn+41qGhsUJXFlIjxI/jSYeZf3ugemDYZldIXIxhvwN6erJGlX4t5h417iFuheZ7l+YVn05N3A==",
      "cpu": [
        "x64"
      ],
      "optional": true,
      "os": [
        "darwin"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/freebsd-arm64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/freebsd-arm64/-/freebsd-arm64-0.19.12.tgz",
      "integrity": "sha512-4aRvFIXmwAcDBw9AueDQ2YnGmz5L6obe5kmPT8Vd+/+x/JMVKCgdcRwH6APrbpNXsPz+K653Qg8HB/oXvXVukA==",
      "cpu": [
        "arm64"
      ],
      "optional": true,
      "os": [
        "freebsd"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/freebsd-x64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/freebsd-x64/-/freebsd-x64-0.19.12.tgz",
      "integrity": "sha512-EYoXZ4d8xtBoVN7CEwWY2IN4ho76xjYXqSXMNccFSx2lgqOG/1TBPW0yPx1bJZk94qu3tX0fycJeeQsKovA8gg==",
      "cpu": [
        "x64"
      ],
      "optional": true,
      "os": [
        "freebsd"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-arm": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-arm/-/linux-arm-0.19.12.tgz",
      "integrity": "sha512-J5jPms//KhSNv+LO1S1TX1UWp1ucM6N6XuL6ITdKWElCu8wXP72l9MM0zDTzzeikVyqFE6U8YAV9/tFyj0ti+w==",
      "cpu": [
        "arm"
      ],
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-arm64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-arm64/-/linux-arm64-0.19.12.tgz",
      "integrity": "sha512-EoTjyYyLuVPfdPLsGVVVC8a0p1BFFvtpQDB/YLEhaXyf/5bczaGeN15QkR+O4S5LeJ92Tqotve7i1jn35qwvdA==",
      "cpu": [
        "arm64"
      ],
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-ia32": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-ia32/-/linux-ia32-0.19.12.tgz",
      "integrity": "sha512-Thsa42rrP1+UIGaWz47uydHSBOgTUnwBwNq59khgIwktK6x60Hivfbux9iNR0eHCHzOLjLMLfUMLCypBkZXMHA==",
      "cpu": [
        "ia32"
      ],
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-loong64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-loong64/-/linux-loong64-0.19.12.tgz",
      "integrity": "sha512-LiXdXA0s3IqRRjm6rV6XaWATScKAXjI4R4LoDlvO7+yQqFdlr1Bax62sRwkVvRIrwXxvtYEHHI4dm50jAXkuAA==",
      "cpu": [
        "loong64"
      ],
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-mips64el": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-mips64el/-/linux-mips64el-0.19.12.tgz",
      "integrity": "sha512-fEnAuj5VGTanfJ07ff0gOA6IPsvrVHLVb6Lyd1g2/ed67oU1eFzL0r9WL7ZzscD+/N6i3dWumGE1Un4f7Amf+w==",
      "cpu": [
        "mips64el"
      ],
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-ppc64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-ppc64/-/linux-ppc64-0.19.12.tgz",
      "integrity": "sha512-nYJA2/QPimDQOh1rKWedNOe3Gfc8PabU7HT3iXWtNUbRzXS9+vgB0Fjaqr//XNbd82mCxHzik2qotuI89cfixg==",
      "cpu": [
        "ppc64"
      ],
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-riscv64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-riscv64/-/linux-riscv64-0.19.12.tgz",
      "integrity": "sha512-2MueBrlPQCw5dVJJpQdUYgeqIzDQgw3QtiAHUC4RBz9FXPrskyyU3VI1hw7C0BSKB9OduwSJ79FTCqtGMWqJHg==",
      "cpu": [
        "riscv64"
      ],
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-s390x": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-s390x/-/linux-s390x-0.19.12.tgz",
      "integrity": "sha512-+Pil1Nv3Umes4m3AZKqA2anfhJiVmNCYkPchwFJNEJN5QxmTs1uzyy4TvmDrCRNT2ApwSari7ZIgrPeUx4UZDg==",
      "cpu": [
        "s390x"
      ],
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-x64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-x64/-/linux-x64-0.19.12.tgz",
      "integrity": "sha512-B71g1QpxfwBvNrfyJdVDexenDIt1CiDN1TIXLbhOw0KhJzE78KIFGX6OJ9MrtC0oOqMWf+0xop4qEU8JrJTwCg==",
      "cpu": [
        "x64"
      ],
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/netbsd-x64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/netbsd-x64/-/netbsd-x64-0.19.12.tgz",
      "integrity": "sha512-3ltjQ7n1owJgFbuC61Oj++XhtzmymoCihNFgT84UAmJnxJfm4sYCiSLTXZtE00VWYpPMYc+ZQmB6xbSdVh0JWA==",
      "cpu": [
        "x64"
      ],
      "optional": true,
      "os": [
        "netbsd"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/openbsd-x64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/openbsd-x64/-/openbsd-x64-0.19.12.tgz",
      "integrity": "sha512-RbrfTB9SWsr0kWmb9srfF+L933uMDdu9BIzdA7os2t0TXhCRjrQyCeOt6wVxr79CKD4c+p+YhCj31HBkYcXebw==",
      "cpu": [
        "x64"
      ],
      "optional": true,
      "os": [
        "openbsd"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/sunos-x64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/sunos-x64/-/sunos-x64-0.19.12.tgz",
      "integrity": "sha512-HKjJwRrW8uWtCQnQOz9qcU3mUZhTUQvi56Q8DPTLLB+DawoiQdjsYq+j+D3s9I8VFtDr+F9CjgXKKC4ss89IeA==",
      "cpu": [
        "x64"
      ],
      "optional": true,
      "os": [
        "sunos"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/win32-arm64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/win32-arm64/-/win32-arm64-0.19.12.tgz",
      "integrity": "sha512-URgtR1dJnmGvX864pn1B2YUYNzjmXkuJOIqG2HdU62MVS4EHpU2946OZoTMnRUHklGtJdJZ33QfzdjGACXhn1A==",
      "cpu": [
        "arm64"
      ],
      "optional": true,
      "os": [
        "win32"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/win32-ia32": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/win32-ia32/-/win32-ia32-0.19.12.tgz",
      "integrity": "sha512-+ZOE6pUkMOJfmxmBZElNOx72NKpIa/HFOMGzu8fqzQJ5kgf6aTGrcJaFsNiVMH4JKpMipyK+7k0n2UXN7a8YKQ==",
      "cpu": [
        "ia32"
      ],
      "optional": true,
      "os": [
        "win32"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/win32-x64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmjs.org/@esbuild/win32-x64/-/win32-x64-0.19.12.tgz",
      "integrity": "sha512-T1QyPSDCyMXaO3pzBkF96E8xMkiRYbUEZADd29SyPGabqxMViNoii+NcK7eWJAEoU6RZyEm5lVSIjTmcdoB9HA==",
      "cpu": [
        "x64"
      ],
      "optional": true,
      "os": [
        "win32"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@formatjs/ecma402-abstract": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/@formatjs/ecma402-abstract/-/ecma402-abstract-2.0.0.tgz",
      "integrity": "sha512-rRqXOqdFmk7RYvj4khklyqzcfQl9vEL/usogncBHRZfZBDOwMGuSRNFl02fu5KGHXdbinju+YXyuR+Nk8xlr/g==",
      "dependencies": {
        "@formatjs/intl-localematcher": "0.5.4",
        "tslib": "^2.4.0"
      }
    },
    "node_modules/@formatjs/fast-memoize": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/@formatjs/fast-memoize/-/fast-memoize-2.2.0.tgz",
      "integrity": "sha512-hnk/nY8FyrL5YxwP9e4r9dqeM6cAbo8PeU9UjyXojZMNvVad2Z06FAVHyR3Ecw6fza+0GH7vdJgiKIVXTMbSBA==",
      "dependencies": {
        "tslib": "^2.4.0"
      }
    },
    "node_modules/@formatjs/icu-messageformat-parser": {
      "version": "2.7.8",
      "resolved": "https://registry.npmjs.org/@formatjs/icu-messageformat-parser/-/icu-messageformat-parser-2.7.8.tgz",
      "integrity": "sha512-nBZJYmhpcSX0WeJ5SDYUkZ42AgR3xiyhNCsQweFx3cz/ULJjym8bHAzWKvG5e2+1XO98dBYC0fWeeAECAVSwLA==",
      "dependencies": {
        "@formatjs/ecma402-abstract": "2.0.0",
        "@formatjs/icu-skeleton-parser": "1.8.2",
        "tslib": "^2.4.0"
      }
    },
    "node_modules/@formatjs/icu-skeleton-parser": {
      "version": "1.8.2",
      "resolved": "https://registry.npmjs.org/@formatjs/icu-skeleton-parser/-/icu-skeleton-parser-1.8.2.tgz",
      "integrity": "sha512-k4ERKgw7aKGWJZgTarIcNEmvyTVD9FYh0mTrrBMHZ1b8hUu6iOJ4SzsZlo3UNAvHYa+PnvntIwRPt1/vy4nA9Q==",
      "dependencies": {
        "@formatjs/ecma402-abstract": "2.0.0",
        "tslib": "^2.4.0"
      }
    },
    "node_modules/@formatjs/intl-localematcher": {
      "version": "0.5.4",
      "resolved": "https://registry.npmjs.org/@formatjs/intl-localematcher/-/intl-localematcher-0.5.4.tgz",
      "integrity": "sha512-zTwEpWOzZ2CiKcB93BLngUX59hQkuZjT2+SAQEscSm52peDW/getsawMcWF1rGRpMCX6D7nSJA3CzJ8gn13N/g==",
      "dependencies": {
        "tslib": "^2.4.0"
      }
    },
    "node_modules/@isaacs/cliui": {
      "version": "8.0.2",
      "resolved": "https://registry.npmjs.org/@isaacs/cliui/-/cliui-8.0.2.tgz",
      "integrity": "sha512-O8jcjabXaleOG9DQ0+ARXWZBTfnP4WNAqzuiJK7ll44AmxGKv/J2M4TPjxjY3znBCfvBXFzucm1twdyFybFqEA==",
      "dev": true,
      "dependencies": {
        "string-width": "^5.1.2",
        "string-width-cjs": "npm:string-width@^4.2.0",
        "strip-ansi": "^7.0.1",
        "strip-ansi-cjs": "npm:strip-ansi@^6.0.1",
        "wrap-ansi": "^8.1.0",
        "wrap-ansi-cjs": "npm:wrap-ansi@^7.0.0"
      },
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@jridgewell/gen-mapping": {
      "version": "0.3.5",
      "resolved": "https://registry.npmjs.org/@jridgewell/gen-mapping/-/gen-mapping-0.3.5.tgz",
      "integrity": "sha512-IzL8ZoEDIBRWEzlCcRhOaCupYyN5gdIK+Q6fbFdPDg6HqX6jpkItn7DFIpW9LQzXG6Df9sA7+OKnq0qlz/GaQg==",
      "dependencies": {
        "@jridgewell/set-array": "^1.2.1",
        "@jridgewell/sourcemap-codec": "^1.4.10",
        "@jridgewell/trace-mapping": "^0.3.24"
      },
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/@jridgewell/resolve-uri": {
      "version": "3.1.2",
      "resolved": "https://registry.npmjs.org/@jridgewell/resolve-uri/-/resolve-uri-3.1.2.tgz",
      "integrity": "sha512-bRISgCIjP20/tbWSPWMEi54QVPRZExkuD9lJL+UIxUKtwVJA8wW1Trb1jMs1RFXo1CBTNZ/5hpC9QvmKWdopKw==",
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/@jridgewell/set-array": {
      "version": "1.2.1",
      "resolved": "https://registry.npmjs.org/@jridgewell/set-array/-/set-array-1.2.1.tgz",
      "integrity": "sha512-R8gLRTZeyp03ymzP/6Lil/28tGeGEzhx1q2k703KGWRAI1VdvPIXdG70VJc2pAMw3NA6JKL5hhFu1sJX0Mnn/A==",
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/@jridgewell/source-map": {
      "version": "0.3.6",
      "resolved": "https://registry.npmjs.org/@jridgewell/source-map/-/source-map-0.3.6.tgz",
      "integrity": "sha512-1ZJTZebgqllO79ue2bm3rIGud/bOe0pP5BjSRCRxxYkE
