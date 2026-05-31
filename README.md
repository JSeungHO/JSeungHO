<div align="center">

# JSeungHO

**3D 지리 · WebGL · 재난 시뮬레이션**

CesiumJS 위에 재난 시뮬레이션, 파도 엔진, 한국 공간데이터를 올리는 프로젝트를 만들고 있습니다.

[![GitHub](https://img.shields.io/badge/GitHub-JSeungHO-181717?style=flat-square&logo=github)](https://github.com/JSeungHO)
[![Cesium](https://img.shields.io/badge/CesiumJS-3D_Globe-6CADDF?style=flat-square)](https://cesium.com/)
[![Vite](https://img.shields.io/badge/Vite-Build-646CFF?style=flat-square&logo=vite&logoColor=white)](https://vite.dev/)
[![Vercel](https://img.shields.io/badge/Deploy-Vercel-000000?style=flat-square&logo=vercel)](https://vercel.com/)

</div>

---

## About

| | |
|---|---|
| **관심 분야** | CesiumJS · WebGL/GLSL · 재난 시뮬레이션 · 디지털 트윈 |
| **주요 스택** | JavaScript · React · Vite · Cesium Ion · VWorld API · .NET |
| **현재 작업** | `geoHazard_engine` 재난 모듈 확장 · `my-wave-engine` 쓰나미 연동 |

---

## Featured Projects

### geoHazard_engine
> 홍수 · 지진 · 쓰나미를 **3D 지구본 위에서** 시각화하는 모듈형 재난 시뮬레이션

[![Repo](https://img.shields.io/badge/Repo-geoHazard__engine-24292f?style=flat-square&logo=github)](https://github.com/JSeungHO/geoHazard_engine)
[![Live Demo](https://img.shields.io/badge/Demo-geohazard--engine.vercel.app-000000?style=flat-square&logo=vercel)](https://geohazard-engine.vercel.app)

`React` `CesiumJS` `Vite` `Vitest` `Playwright`

---

### cesium-korean-service
> **VWorld WMTS** 배경지도 + Cesium World Terrain 한국 3D 지도 서비스

[![Repo](https://img.shields.io/badge/Repo-cesium--korean--service-24292f?style=flat-square&logo=github)](https://github.com/JSeungHO/cesium-korean-service)
[![Live Demo](https://img.shields.io/badge/Demo-cesium--korean--service.vercel.app-000000?style=flat-square&logo=vercel)](https://cesium-korean-service.vercel.app)

`CesiumJS` `VWorld API` `Vite` `Vercel`

---

### my-wave-engine
> **Gerstner wave** WebGL 파도 엔진 · Cesium adapter · .NET CLI 자동화

[![Repo](https://img.shields.io/badge/Repo-my--wave--engine-24292f?style=flat-square&logo=github)](https://github.com/JSeungHO/my-wave-engine)

`WebGL` `GLSL` `CesiumJS` `C#` `Vite`

---

### grid-city
> Vite 기반 그리드 도시 시각화 실험

[![Repo](https://img.shields.io/badge/Repo-grid--city-24292f?style=flat-square&logo=github)](https://github.com/JSeungHO/grid-city)

`Vite` `JavaScript` `WebGL`

---

## Architecture

```mermaid
graph TD
    A[geoHazard_engine<br/>재난 시뮬레이션 메인] --> B[my-wave-engine<br/>WebGL 3D 파도]
    A --> C[cesium-korean-service<br/>VWorld 한국 지도]
    B -.->|쓰나미 연동 예정| A
    C -.->|공간데이터·레이어 UI| A
```

---

## GitHub Stats

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=JSeungHO&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true)

![Top langs](https://github-readme-stats.vercel.app/api/top-langs/?username=JSeungHO&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

**Portfolio entry point:** [geoHazard_engine](https://github.com/JSeungHO/geoHazard_engine) → [cesium-korean-service](https://github.com/JSeungHO/cesium-korean-service) → [my-wave-engine](https://github.com/JSeungHO/my-wave-engine)

</div>
