# [poppy-devops](https://github.com/x-poppy/poppy-devops)

## Table of Contents

- [Description](#description)
- [Preparation](#preparation)
- [Usage](#usage)
- [Related Efforts](#related-efforts)
- [Maintainers](#maintainers)
- [Contributing](#contributing)
- [License](#license)

## Description

## Preparation

http://www.redis.cn/commands.html

[Redis Client](http://getmedis.com/)

## Usage

```bash
docker swarm init
docker swarm join --token SWMTKN-1-1k0sqv8rxbwhlwoi2hith5hi1e50y050ly10s22m5tbz7yqpjs-14mrese70xbin79r68ack01qd 172.19.50.116:2377

docker stack deploy --prune -c /opt/ops/poppy-devops/xpoppy/dev/docker-compose.yml xpoppy 

--with-registry-auth
```

visit [augejs.github.io](https://github.com/augejs/augejs.github.io). :tada:

## Related Efforts

- [Art of Readme](https://github.com/noffle/art-of-readme) - 💌 Learn the art of writing quality READMEs.
- [open-source-template](https://github.com/davidbgk/open-source-template/) - A README template to encourage open-source contributions.

## Maintainers

[Alex Zhang](https://github.com/alex-zhang).

## Contributing

## License

[MIT](LICENSE) © xpoppy
