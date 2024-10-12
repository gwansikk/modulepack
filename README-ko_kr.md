<div align="center">

<h1>modulepack (PoC)</h1>
<p><b>여러 버전의 모듈을 하나의 유니버셜 모듈로 결합하기</b></p>

[![GitHub License](https://img.shields.io/github/license/gwansikk/modulepack?labelColor=black&color=black)](https://github.com/gwansikk/modulepack?tab=MIT-1-ov-file)

[English](https://github.com/gwansikk/modulepack/blob/main/README.md)
&nbsp;&nbsp;•&nbsp;&nbsp;
[한국어](https://github.com/gwansikk/modulepack/blob/main/README-ko_kr.md)

</div>

## modulepack란?

> [!CAUTION]
> modulepack은 현재 개발 중입니다. 제공된 API는 변경될 수 있습니다.

여러 버전의 모듈을 하나의 유니버설 모듈로 통합함으로써 브레이킹 체인지로 인한 호환성 문제를 해결하는 방법을 제공합니다. 이를 통해 개발자는 다양한 버전의 모듈을 사용하는 프로젝트에서 발생할 수 있는 충돌을 최소화하고, 코드의 유지보수성을 높일 수 있습니다. 유니버설 모듈은 각 버전의 기능을 지원하면서도, 사용자에게 일관된 인터페이스를 제공하여 개발 경험을 향상시키는 데 기여합니다.

### 이것은 번들러가 아닙니다

modulepack은 번들러가 아닙니다. 번들러가 여러 모듈을 하나의 파일로 묶는 것을 목표로 하는 반면, modulepack은 여러 버전의 모듈을 하나의 모듈로 결합하는 데 중점을 둡니다.

## 주요 기능

- 🎒 유니버셜 모듈: 여러 버전의 모듈을 하나의 모듈로 결합합니다. 높은 버전 커버리지를 가진 라이브러리를 생성합니다.
- 🎭 버전 관리: 특정 버전 간에 전환하거나 필요에 따라 마이그레이션할 수 있습니다.
- 🧪 모듈 테스트: 여러 버전에 대한 해당 테스트 코드를 한 번에 관리합니다.

## 기여하기

해당 프로젝트에 기여하고 싶다면 아래 문서를 참고해주세요.

[CONTRIBUTING.md](https://github.com/gwansikk/modulepack/blob/main/CONTRIBUTING.md)

### 기여자

[![contributors](https://contrib.rocks/image?repo=gwansikk/modulepack)](https://github.com/gwansikk/modulepack/contributors)

## 라이선스

See [LICENSE](https://github.com/gwansikk/modulepack/blob/main/LICENSE) for more information.

MIT © [gwansikk](https://github.com/gwansikk)
