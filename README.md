# My FFlags Docs

Disable player textures models (they will be gray)

```json
{
  "DFIntTextureCompositorActiveJobs": "0"
}
```

Renders

```json
{
  "FFlagRenderSunRays": "False",
  "FFlagRenderTerrainDetail": "False",
  "FFlagRenderTerrain": "True",
  "FFlagRenderGrass": "False",
  "FFlagRenderCSGGrid": "False",
  "FFlagRenderVolumetrics": "False",
  "FFlagRenderLightQuality": "False",
  "FFlagRenderGlobalShadows": "False",
  "FFlagRenderMotionBlur": "False",
  "FFlagRenderShadows": "False",
  "FFlagRenderHttpTextureEnable": "False",
  "FFlagRenderEnableFRM": "False",
  "FFlagRenderShadowBlob": "False"
  "FFlagRenderTerrainClipmap": "False",
  "FFlagRenderVolumetricsDebug": "False",
  "FFlagRenderDepthOfField": "False",
  "FFlagRenderBloom": "False",
}
```

Set sky gray

```json
{
  "FFlagDebugSkyGray": "True"
}
```

Textures quality

```json
{
  "DFFlagTextureQualityOverrideEnabled": "0"
}
```

Light post rendering

```json
{
  "FFlagDisablePostFx": "True"
}
```

Voxel render Techonology (better for high FPS)

```json
{
  "DFFlagDebugRenderForceTechnologyVoxel": "True"
}
```

Disables smoothing

```json
{
  "FIntDebugForceMSAASamples": "1"
}
```

Disables player shadows

```json
{
  "FIntRenderShadowIntensity": 0
}
```

Disables grass

```json
{
  "FIntFRMMinGrassDistance": "0",
  "FIntFRMMaxGrassDistance": "0"
}
```

Disables antialiasing

```json
{
  "FIntDebugForceMSAASamples": 0
}
```

Low Quality lights

```json
{
  "FFlagNewLightAttenuation": "True"
}
```

Set max FPS

```json
{
  "DFIntTaskSchedulerTargetFps": "9999"
}
```

Set max threads

```json
{
  "DFIntTaskSchedulerMaxThreads": "15"
}
```

Enable TweenService optimization (smoothed animation and more)

```json
{
  "FFlagTweenOptimizations": "True"
}
```

Enables Terrain optimization

```json
{
  "FFlagEnableTerrainOptimizations": "True",
  "FFlagEnableTerrainFoliageOptimizations": "True"
}
```

Set lights on objects smoother

```json
{
  "FFlagFastGPULightCulling3": "True"
}
```

Stop render delay

```json
{
  "DFIntRenderingThrottleDelayInMS": "1"
}
```

Disables crash reports (for lower ping)

```json
{
  "FFlagDebugDisableTelemetryEventIngest": "True",
  "DFFlagDisableFastLogTelemetry": "True",
  "FFlagDebugDisableTelemetryPoint": "True",
  "FFlagDebugDisableTelemetryEphemeralCounter": "True",
  "FFlagDebugDisableTelemetryV2Stat": "True",
  "FFlagDebugDisableTelemetryEphemeralStat": "True",
  "FFlagDebugDisableTelemetryV2Event": "True",
  "DFFlagBrowserTrackerIdTelemetryEnabled": "False",
  "DFFlagEnableLightstepReporting2": "False",
  "DFStringTelemetryV2Url": "null"
}
```

Another Network settings (for lower ping)

```json
{
  "FLogNetwork": "7",
  "FFlagNewNetworking": "False",
  "DFIntS2PhysicsSenderRate": "250"
}
```

Disables additional processing

```json
{
  "FFlagHandleAltEnterFullscreenManually": "False"
}
```

Disables scaling to fit screens

```json
{
  "DFFlagDisableDPIScale": "True"
}
```

Disables all r15 animation (use only in r6 games)

```json
{
  "FFlagUseNewAnimationSystem": "False"
}
```

Lower graphics

```json
{
  "FFlagFixGraphicsQuality": "True",
  "FFlagCommitToGraphicsQualityFix": "True"
}
```

Enables new method input (for Mouse,keyboard and more)

```json
{
  "FFlagEnableNewInput": "True"
}
```

Disable FPS Display (it doesn't affect fps)

```json
{
  "FFlagDebugDisplayFPS": "False"
}
```

Another settings (for models/meshes and more)

```json
{
  "FStringPartTexturePackTablePre2022": "",
  "FStringPartTexturePackTable2022": "",
  "FStringTerrainMaterialTablePre2022": "",
  "FStringTerrainMaterialTable2022": "",
  "DFIntCSGLevelOfDetailSwitchingDistance": "0",
  "DFIntCSGLevelOfDetailSwitchingDistanceL12": "0",
  "DFIntCSGLevelOfDetailSwitchingDistanceL23": "0",
  "DFIntCSGLevelOfDetailSwitchingDistanceL34": "0",
  "FFlagSimIslandizerManager": "False"
}
```

Full config 
```json
{
  "DFIntTaskSchedulerTargetFps": "999999",
  "FIntTerrainArraySliceSize": "0",
  "FIntRenderShadowIntensity": "0",
  "FLogNetwork": "7",
  "FFlagHandleAltEnterFullscreenManually": "False",
  "FFlagDebugGraphicsPreferD3D11": "True",
  "FFlagDebugGraphicsPreferD3D11FL10": "False",
  "DFFlagTextureQualityOverrideEnabled": "True",
  "DFIntTextureQualityOverride": "0",
  "FFlagDisablePostFx": "True",
  "DFFlagDisableDPIScale": "True",
  "DFFlagDebugRenderForceTechnologyVoxel": "True",
  "FIntDebugForceMSAASamples": "1",
  "FIntFRMMinGrassDistance": "0",
  "FIntFRMMaxGrassDistance": "0",
  "FIntRenderGrassDetailStrands": "0",
  "FIntRenderGrassHeightScaler": "0",
  "FStringPartTexturePackTablePre2022": "",
  "FStringPartTexturePackTable2022": "",
  "FStringTerrainMaterialTablePre2022": "",
  "FStringTerrainMaterialTable2022": "",
  "DFIntCSGLevelOfDetailSwitchingDistance": "0",
  "DFIntCSGLevelOfDetailSwitchingDistanceL12": "0",
  "DFIntCSGLevelOfDetailSwitchingDistanceL23": "0",
  "DFIntCSGLevelOfDetailSwitchingDistanceL34": "0",
  "FFlagDebugSkyGray": "True",
  "DFIntTextureCompositorActiveJobs": "0",
  "FFlagRenderSunRays": "False",
  "FFlagRenderTerrainDetail": "False",
  "FFlagRenderTerrain": "True",
  "FFlagRenderGrass": "False",
  "FFlagRenderCSGGrid": "False",
  "FFlagRenderVolumetrics": "False",
  "FFlagRenderLightQuality": "False",
  "FFlagRenderGlobalShadows": "False",
  "FFlagRenderMotionBlur": "False",
  "FFlagRenderShadows": "False",
  "FFlagRenderHttpTextureEnable": "False",
  "FFlagRenderEnableFRM": "False",
  "FFlagRenderShadowBlob": "False",
  "DFIntTaskSchedulerMaxThreads": "30",
  "FFlagRenderTerrainClipmap": "False",
  "FFlagRenderVolumetricsDebug": "False",
  "FFlagRenderDepthOfField": "False",
  "FFlagRenderBloom": "False",
  "FFlagDebugCrashReports": "False",
  "DFStringAltHttpPointsReporterUrl": "null",
  "DFStringLightstepHTTPTransportUrlPath": "null",
  "FFlagTweenOptimizations": "True",
  "FFlagUseNewAnimationSystem": "False",
  "FFlagDebugDisableTelemetryEventIngest": "True",
  "DFFlagDebugPerfMode": "False",
  "DFFlagBrowserTrackerIdTelemetryEnabled": "False",
  "DFStringTelemetryV2Url": "null",
  "FFlagFixGraphicsQuality": "True",
  "FFlagEnableNewHeapSnapshots": "False",
  "FFlagNewNetworking": "False",
  "FFlagPreloadAllFonts": "False",
  "FStringGamesUrlPath": "/games/",
  "DFFlagDisableFastLogTelemetry": "True",
  "FFlagNewLightAttenuation": "True",
  "FFlagEnableTerrainFoliageOptimizations": "True",
  "FFlagDebugDisableTelemetryPoint": "True",
  "DFStringAltTelegrafHTTPTransportUrl": "null",
  "FFlagEnableHumanoidLuaSideCaching": "False",
  "FFlagFastGPULightCulling3": "True",
  "FFlagEnableNewInput": "True",
  "FFlagCommitToGraphicsQualityFix": "True",
  "FFlagAnimatePhysics": "False",
  "FFlagSimIslandizerManager": "false",
  "FFlagDebugDisableTelemetryEphemeralCounter": "True",
  "FFlagDebugDisableTelemetryV2Stat": "True",
  "FFlagUseUnifiedRenderStepped": "False",
  "FFlagUseParticlesV2": "False",
  "FFlagTaskSchedulerLimitTargetFpsTo2402": "False",
  "FFlagUseDeferredContext": "False",
  "FFlagOptimizeEmotes": "False",
  "DFStringLightstepToken": "null",
  "FFlagFixScalingModelRendering": "False",
  "DFIntNewRunningBaseAltitudeD": "45",
  "FFlagDebugDisableTelemetryV2Counter": "True",
  "DFIntClientLightingTechnologyChangedTelemetryHundredthsPercent": "0",
  "FFlagUseDynamicSun": "False",
  "DFFlagDebugPauseVoxelizer": "True",
  "DFStringTelegrafHTTPTransportUrl": "null",
  "DFStringRobloxAnalyticsURL": "null",
  "DFIntLightstepHTTPTransportHundredthsPercent2": "0",
  "DFStringLightstepHTTPTransportUrlHost": "null",
  "DFStringCrashUploadToBacktraceWindowsPlayerToken": "null",
  "FFlagEnableTerrainOptimizations": "True",
  "FFlagLuaAppSystemBar": "False",
  "FFlagFixMeshPartScaling": "False",
  "DFStringCrashUploadToBacktraceBaseUrl": "null",
  "DFStringCrashUploadToBacktraceMacPlayerToken": "null",
  "DFIntS2PhysicsSenderRate": "250",
  "FFlagEnableLightAttachToPart": "False",
  "FFlagDebugDisableTelemetryEphemeralStat": "True",
  "FFlagDebugDisableTelemetryV2Event": "True",
  "FFlagAdServiceEnabled": "False",
  "DFStringHttpPointsReporterUrl": "null",
  "FStringCoreScriptBacktraceErrorUploadToken": "null",
  "FFlagDebugDisplayFPS": "False",
  "DFFlagEnableLightstepReporting2": "False",
  "DFIntRenderingThrottleDelayInMS": "1",
  "DFIntRunningBaseOrientationP": "115",
  "DFFlagBaseNetworkMetrics": "False"
}
```

!!! Use these fflags at your own risk !!!
