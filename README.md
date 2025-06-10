# chatgptcrashreport

---- Minecraft Crash Report ----
// Embeddium instance tainted by mods: [sodiumoptionsapi, sodiumextras]
// Please do not reach out for Embeddium support without removing these mods first.
// -------
// You should try our sister game, Minceraft!

Time: 2025-06-11 03:30:51
Description: mouseClicked event handler

java.lang.NoSuchFieldError: invariant
	at dev.electrolyte.gm_construct.data.MaterialTraitsGeneration.<clinit>(MaterialTraitsGeneration.java:48) ~[gm_construct-1.0.5.jar%23344!/:1.0.5] {re:classloading}
	at dev.electrolyte.gm_construct.data.GMCDynamicDataPack.generateAllMaterialData(GMCDynamicDataPack.java:77) ~[gm_construct-1.0.5.jar%23344!/:1.0.5] {re:classloading}
	at dev.electrolyte.gm_construct.event.GMCForgeEventHandler.reloadResources(GMCForgeEventHandler.java:22) ~[gm_construct-1.0.5.jar%23344!/:1.0.5] {re:classloading}
	at dev.electrolyte.gm_construct.event.__GMCForgeEventHandler_reloadResources_AddReloadListenerEvent.invoke(.dynamic) ~[gm_construct-1.0.5.jar%23344!/:1.0.5] {re:classloading,pl:eventbus:B}
	at net.minecraftforge.eventbus.ASMEventHandler.invoke(ASMEventHandler.java:73) ~[eventbus-6.0.5.jar%23137!/:?] {}
	at net.minecraftforge.eventbus.EventBus.post(EventBus.java:315) ~[eventbus-6.0.5.jar%23137!/:?] {}
	at net.minecraftforge.eventbus.EventBus.post(EventBus.java:296) ~[eventbus-6.0.5.jar%23137!/:?] {}
	at net.minecraftforge.event.ForgeEventFactory.onResourceReload(ForgeEventFactory.java:810) ~[forge-1.20.1-47.4.0-universal.jar%23433!/:?] {re:mixin,re:classloading,pl:mixin:APP:aether.mixins.json:common.ForgeEventFactoryMixin,pl:mixin:APP:modernfix-forge.mixins.json:perf.potential_spawns_alloc.ForgeEventFactoryMixin,pl:mixin:A}
	at net.minecraft.server.ReloadableServerResources.m_247740_(ReloadableServerResources.java:77) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:placebo.mixins.json:ServerResourcesMixin,pl:mixin:APP:balm.mixins.json:ReloadableServerResourcesMixin,pl:mixin:A}
	at net.minecraft.server.WorldLoader.m_214362_(WorldLoader.java:38) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,re:classloading,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.WorldLoaderMixin,pl:mixin:APP:modernfix-forge.mixins.json:core.WorldLoaderMixin,pl:mixin:APP:ldlib-common.mixins.json:WorldLoaderMixin,pl:mixin:A}
	at net.minecraft.client.gui.screens.worldselection.CreateWorldScreen.m_232896_(CreateWorldScreen.java:125) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.worldselection.WorldSelectionList.m_233213_(WorldSelectionList.java:167) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.worldselection.WorldSelectionList.<init>(WorldSelectionList.java:93) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.worldselection.SelectWorldScreen.m_7856_(SelectWorldScreen.java:54) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:classloading}
	at net.minecraft.client.gui.screens.Screen.m_6575_(Screen.java:321) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:computing_frames,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:aether.mixins.json:client.accessor.ScreenAccessor,pl:mixin:APP:balm.mixins.json:ScreenAccessor,pl:mixin:APP:patchouli_xplat.mixins.json:client.AccessorScreen,pl:mixin:APP:cumulus_menus.mixins.json:client.accessor.ScreenAccessor,pl:mixin:APP:quark.mixins.json:client.ScreenMixin,pl:mixin:APP:ae2.mixins.json:WrappedGenericStackTooltipModIdMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91152_(Minecraft.java:1007) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.sodiumextras.json:impl.fps.GpuUsageMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.dedicated_reload_executor.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.blast_search_trees.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.world_leaks.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.concurrency.MinecraftMixin,pl:mixin:APP:modernfix-forge.mixins.json:feature.measure_time.MinecraftMixin_Forge,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMinecraft,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:carryon.mixins.json:MinecraftMixin,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:mixins.codechickenlib.json:MinecraftMixin,pl:mixin:APP:tofucraft.mixins.json:client.MinecraftMixin,pl:mixin:APP:ae2.mixins.json:PickColorMixin,pl:mixin:APP:moonlight-common.mixins.json:MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:configuration.mixins.json:MinecraftMixin,pl:mixin:APP:flywheel.mixins.json:PausedPartialTickAccessor,pl:mixin:APP:quark.mixins.json:client.MinecraftMixin,pl:mixin:APP:mixins.irons_spellbooks.json:MinecraftMixin,pl:mixin:APP:immediatelyfast-common.mixins.json:core.MixinMinecraftClient,pl:mixin:APP:create.mixins.json:client.WindowResizeMixin,pl:mixin:APP:embeddium.mixins.json:core.MinecraftClientMixin,pl:mixin:APP:embeddium.mixins.json:core.render.MinecraftAccessor,pl:mixin:APP:modernfix-common.mixins.json:feature.remove_telemetry.MinecraftMixin_Telemetry,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.TitleScreen.m_279796_(TitleScreen.java:159) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:computing_frames,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:aether.mixins.json:client.TitleScreenMixin,pl:mixin:APP:aether.mixins.json:client.accessor.TitleScreenAccessor,pl:mixin:APP:cumulus_menus.mixins.json:client.accessor.TitleScreenAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.components.Button.m_5691_(Button.java:38) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:aether.mixins.json:client.accessor.ButtonAccessor,pl:mixin:APP:moonlight.mixins.json:ButtonAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.components.AbstractButton.m_5716_(AbstractButton.java:55) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:tacz.mixins.json:client.AbstractButtonMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.components.AbstractWidget.m_6375_(AbstractWidget.java:175) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.components.events.ContainerEventHandler.m_6375_(ContainerEventHandler.java:38) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,re:computing_frames,re:classloading}
	at net.minecraft.client.gui.screens.TitleScreen.m_6375_(TitleScreen.java:294) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:computing_frames,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:aether.mixins.json:client.TitleScreenMixin,pl:mixin:APP:aether.mixins.json:client.accessor.TitleScreenAccessor,pl:mixin:APP:cumulus_menus.mixins.json:client.accessor.TitleScreenAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.MouseHandler.m_168084_(MouseHandler.java:92) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:ldlib-common.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMouseHandler,pl:mixin:APP:balm.mixins.json:MouseHandlerAccessor,pl:mixin:APP:tacz.mixins.json:client.MouseHandlerMixin,pl:mixin:APP:mixins.cofhcore.json:MouseHandlerMixin,pl:mixin:APP:brewinandchewin.mixins.json:client.TipsyMouseHandlerMixin,pl:mixin:APP:create.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.Screen.m_96579_(Screen.java:437) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:computing_frames,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:aether.mixins.json:client.accessor.ScreenAccessor,pl:mixin:APP:balm.mixins.json:ScreenAccessor,pl:mixin:APP:patchouli_xplat.mixins.json:client.AccessorScreen,pl:mixin:APP:cumulus_menus.mixins.json:client.accessor.ScreenAccessor,pl:mixin:APP:quark.mixins.json:client.ScreenMixin,pl:mixin:APP:ae2.mixins.json:WrappedGenericStackTooltipModIdMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.MouseHandler.m_91530_(MouseHandler.java:89) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:ldlib-common.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMouseHandler,pl:mixin:APP:balm.mixins.json:MouseHandlerAccessor,pl:mixin:APP:tacz.mixins.json:client.MouseHandlerMixin,pl:mixin:APP:mixins.cofhcore.json:MouseHandlerMixin,pl:mixin:APP:brewinandchewin.mixins.json:client.TipsyMouseHandlerMixin,pl:mixin:APP:create.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.MouseHandler.m_168091_(MouseHandler.java:189) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:ldlib-common.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMouseHandler,pl:mixin:APP:balm.mixins.json:MouseHandlerAccessor,pl:mixin:APP:tacz.mixins.json:client.MouseHandlerMixin,pl:mixin:APP:mixins.cofhcore.json:MouseHandlerMixin,pl:mixin:APP:brewinandchewin.mixins.json:client.TipsyMouseHandlerMixin,pl:mixin:APP:create.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:102) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B}
	at net.minecraft.client.MouseHandler.m_91565_(MouseHandler.java:188) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:ldlib-common.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMouseHandler,pl:mixin:APP:balm.mixins.json:MouseHandlerAccessor,pl:mixin:APP:tacz.mixins.json:client.MouseHandlerMixin,pl:mixin:APP:mixins.cofhcore.json:MouseHandlerMixin,pl:mixin:APP:brewinandchewin.mixins.json:client.TipsyMouseHandlerMixin,pl:mixin:APP:create.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at org.lwjgl.glfw.GLFWMouseButtonCallbackI.callback(GLFWMouseButtonCallbackI.java:43) ~[lwjgl-glfw-3.3.1.jar%2386!/:build 7] {}
	at org.lwjgl.system.JNI.invokeV(Native Method) ~[lwjgl-3.3.1.jar%2398!/:build 7] {}
	at org.lwjgl.glfw.GLFW.glfwWaitEventsTimeout(GLFW.java:3474) ~[lwjgl-glfw-3.3.1.jar%2386!/:build 7] {re:mixin}
	at com.mojang.blaze3d.systems.RenderSystem.limitDisplayFPS(RenderSystem.java:237) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:flywheel.mixins.json:RenderTexturesMixin,pl:mixin:APP:embeddium.mixins.json:workarounds.event_loop.RenderSystemMixin,pl:mixin:A}
	at net.minecraft.client.Minecraft.m_91383_(Minecraft.java:1173) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.sodiumextras.json:impl.fps.GpuUsageMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.dedicated_reload_executor.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.blast_search_trees.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.world_leaks.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.concurrency.MinecraftMixin,pl:mixin:APP:modernfix-forge.mixins.json:feature.measure_time.MinecraftMixin_Forge,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMinecraft,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:carryon.mixins.json:MinecraftMixin,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:mixins.codechickenlib.json:MinecraftMixin,pl:mixin:APP:tofucraft.mixins.json:client.MinecraftMixin,pl:mixin:APP:ae2.mixins.json:PickColorMixin,pl:mixin:APP:moonlight-common.mixins.json:MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:configuration.mixins.json:MinecraftMixin,pl:mixin:APP:flywheel.mixins.json:PausedPartialTickAccessor,pl:mixin:APP:quark.mixins.json:client.MinecraftMixin,pl:mixin:APP:mixins.irons_spellbooks.json:MinecraftMixin,pl:mixin:APP:immediatelyfast-common.mixins.json:core.MixinMinecraftClient,pl:mixin:APP:create.mixins.json:client.WindowResizeMixin,pl:mixin:APP:embeddium.mixins.json:core.MinecraftClientMixin,pl:mixin:APP:embeddium.mixins.json:core.render.MinecraftAccessor,pl:mixin:APP:modernfix-common.mixins.json:feature.remove_telemetry.MinecraftMixin_Telemetry,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:718) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.sodiumextras.json:impl.fps.GpuUsageMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.dedicated_reload_executor.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.blast_search_trees.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.world_leaks.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.concurrency.MinecraftMixin,pl:mixin:APP:modernfix-forge.mixins.json:feature.measure_time.MinecraftMixin_Forge,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMinecraft,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:carryon.mixins.json:MinecraftMixin,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:mixins.codechickenlib.json:MinecraftMixin,pl:mixin:APP:tofucraft.mixins.json:client.MinecraftMixin,pl:mixin:APP:ae2.mixins.json:PickColorMixin,pl:mixin:APP:moonlight-common.mixins.json:MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:configuration.mixins.json:MinecraftMixin,pl:mixin:APP:flywheel.mixins.json:PausedPartialTickAccessor,pl:mixin:APP:quark.mixins.json:client.MinecraftMixin,pl:mixin:APP:mixins.irons_spellbooks.json:MinecraftMixin,pl:mixin:APP:immediatelyfast-common.mixins.json:core.MixinMinecraftClient,pl:mixin:APP:create.mixins.json:client.WindowResizeMixin,pl:mixin:APP:embeddium.mixins.json:core.MinecraftClientMixin,pl:mixin:APP:embeddium.mixins.json:core.render.MinecraftAccessor,pl:mixin:APP:modernfix-common.mixins.json:feature.remove_telemetry.MinecraftMixin_Telemetry,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:218) ~[minecraft-1.20.1-client.jar:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:flywheel.mixins.json:ClientMainMixin,pl:mixin:APP:cryonicconfig.mixins.json:client.MainMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:569) ~[?:?] {re:mixin}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:111) ~[fmlloader-1.20.1-47.4.0.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:99) ~[fmlloader-1.20.1-47.4.0.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$makeService$0(CommonClientLaunchHandler.java:25) ~[fmlloader-1.20.1-47.4.0.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:108) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:78) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:569) ~[?:?] {re:mixin}
	at io.github.zekerzhayard.forgewrapper.installer.Main.main(Main.java:67) ~[?:?] {}
	at org.prismlauncher.launcher.impl.StandardLauncher.launch(StandardLauncher.java:105) ~[?:?] {}
	at org.prismlauncher.EntryPoint.listen(EntryPoint.java:129) ~[?:?] {}
	at org.prismlauncher.EntryPoint.main(EntryPoint.java:70) ~[?:?] {}


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Render thread
Suspected Mod: 
	Greg's Modern Construct (gm_construct), Version: 1.0.5
		Issue tracker URL: https://github.com/Electrolyte220/GregsModernConstruct/issues
		at TRANSFORMER/gm_construct@1.0.5/dev.electrolyte.gm_construct.data.MaterialTraitsGeneration.<clinit>(MaterialTraitsGeneration.java:48)
Stacktrace:
	at dev.electrolyte.gm_construct.data.MaterialTraitsGeneration.<clinit>(MaterialTraitsGeneration.java:48) ~[gm_construct-1.0.5.jar%23344!/:1.0.5] {re:classloading}
	at dev.electrolyte.gm_construct.data.GMCDynamicDataPack.generateAllMaterialData(GMCDynamicDataPack.java:77) ~[gm_construct-1.0.5.jar%23344!/:1.0.5] {re:classloading}
	at dev.electrolyte.gm_construct.event.GMCForgeEventHandler.reloadResources(GMCForgeEventHandler.java:22) ~[gm_construct-1.0.5.jar%23344!/:1.0.5] {re:classloading}
	at dev.electrolyte.gm_construct.event.__GMCForgeEventHandler_reloadResources_AddReloadListenerEvent.invoke(.dynamic) ~[gm_construct-1.0.5.jar%23344!/:1.0.5] {re:classloading,pl:eventbus:B}
	at net.minecraftforge.eventbus.ASMEventHandler.invoke(ASMEventHandler.java:73) ~[eventbus-6.0.5.jar%23137!/:?] {}
	at net.minecraftforge.eventbus.EventBus.post(EventBus.java:315) ~[eventbus-6.0.5.jar%23137!/:?] {}
	at net.minecraftforge.eventbus.EventBus.post(EventBus.java:296) ~[eventbus-6.0.5.jar%23137!/:?] {}
	at net.minecraftforge.event.ForgeEventFactory.onResourceReload(ForgeEventFactory.java:810) ~[forge-1.20.1-47.4.0-universal.jar%23433!/:?] {re:mixin,re:classloading,pl:mixin:APP:aether.mixins.json:common.ForgeEventFactoryMixin,pl:mixin:APP:modernfix-forge.mixins.json:perf.potential_spawns_alloc.ForgeEventFactoryMixin,pl:mixin:A}
	at net.minecraft.server.ReloadableServerResources.m_247740_(ReloadableServerResources.java:77) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:placebo.mixins.json:ServerResourcesMixin,pl:mixin:APP:balm.mixins.json:ReloadableServerResourcesMixin,pl:mixin:A}
	at net.minecraft.server.WorldLoader.m_214362_(WorldLoader.java:38) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,re:classloading,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.WorldLoaderMixin,pl:mixin:APP:modernfix-forge.mixins.json:core.WorldLoaderMixin,pl:mixin:APP:ldlib-common.mixins.json:WorldLoaderMixin,pl:mixin:A}
	at net.minecraft.client.gui.screens.worldselection.CreateWorldScreen.m_232896_(CreateWorldScreen.java:125) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.worldselection.WorldSelectionList.m_233213_(WorldSelectionList.java:167) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.worldselection.WorldSelectionList.<init>(WorldSelectionList.java:93) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.worldselection.SelectWorldScreen.m_7856_(SelectWorldScreen.java:54) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:classloading}
	at net.minecraft.client.gui.screens.Screen.m_6575_(Screen.java:321) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:computing_frames,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:aether.mixins.json:client.accessor.ScreenAccessor,pl:mixin:APP:balm.mixins.json:ScreenAccessor,pl:mixin:APP:patchouli_xplat.mixins.json:client.AccessorScreen,pl:mixin:APP:cumulus_menus.mixins.json:client.accessor.ScreenAccessor,pl:mixin:APP:quark.mixins.json:client.ScreenMixin,pl:mixin:APP:ae2.mixins.json:WrappedGenericStackTooltipModIdMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91152_(Minecraft.java:1007) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.sodiumextras.json:impl.fps.GpuUsageMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.dedicated_reload_executor.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.blast_search_trees.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.world_leaks.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.concurrency.MinecraftMixin,pl:mixin:APP:modernfix-forge.mixins.json:feature.measure_time.MinecraftMixin_Forge,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMinecraft,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:carryon.mixins.json:MinecraftMixin,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:mixins.codechickenlib.json:MinecraftMixin,pl:mixin:APP:tofucraft.mixins.json:client.MinecraftMixin,pl:mixin:APP:ae2.mixins.json:PickColorMixin,pl:mixin:APP:moonlight-common.mixins.json:MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:configuration.mixins.json:MinecraftMixin,pl:mixin:APP:flywheel.mixins.json:PausedPartialTickAccessor,pl:mixin:APP:quark.mixins.json:client.MinecraftMixin,pl:mixin:APP:mixins.irons_spellbooks.json:MinecraftMixin,pl:mixin:APP:immediatelyfast-common.mixins.json:core.MixinMinecraftClient,pl:mixin:APP:create.mixins.json:client.WindowResizeMixin,pl:mixin:APP:embeddium.mixins.json:core.MinecraftClientMixin,pl:mixin:APP:embeddium.mixins.json:core.render.MinecraftAccessor,pl:mixin:APP:modernfix-common.mixins.json:feature.remove_telemetry.MinecraftMixin_Telemetry,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.TitleScreen.m_279796_(TitleScreen.java:159) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:computing_frames,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:aether.mixins.json:client.TitleScreenMixin,pl:mixin:APP:aether.mixins.json:client.accessor.TitleScreenAccessor,pl:mixin:APP:cumulus_menus.mixins.json:client.accessor.TitleScreenAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.components.Button.m_5691_(Button.java:38) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:aether.mixins.json:client.accessor.ButtonAccessor,pl:mixin:APP:moonlight.mixins.json:ButtonAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.components.AbstractButton.m_5716_(AbstractButton.java:55) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:tacz.mixins.json:client.AbstractButtonMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.components.AbstractWidget.m_6375_(AbstractWidget.java:175) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.components.events.ContainerEventHandler.m_6375_(ContainerEventHandler.java:38) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,re:computing_frames,re:classloading}
	at net.minecraft.client.gui.screens.TitleScreen.m_6375_(TitleScreen.java:294) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:computing_frames,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:aether.mixins.json:client.TitleScreenMixin,pl:mixin:APP:aether.mixins.json:client.accessor.TitleScreenAccessor,pl:mixin:APP:cumulus_menus.mixins.json:client.accessor.TitleScreenAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.MouseHandler.m_168084_(MouseHandler.java:92) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:ldlib-common.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMouseHandler,pl:mixin:APP:balm.mixins.json:MouseHandlerAccessor,pl:mixin:APP:tacz.mixins.json:client.MouseHandlerMixin,pl:mixin:APP:mixins.cofhcore.json:MouseHandlerMixin,pl:mixin:APP:brewinandchewin.mixins.json:client.TipsyMouseHandlerMixin,pl:mixin:APP:create.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.Screen.m_96579_(Screen.java:437) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:computing_frames,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:aether.mixins.json:client.accessor.ScreenAccessor,pl:mixin:APP:balm.mixins.json:ScreenAccessor,pl:mixin:APP:patchouli_xplat.mixins.json:client.AccessorScreen,pl:mixin:APP:cumulus_menus.mixins.json:client.accessor.ScreenAccessor,pl:mixin:APP:quark.mixins.json:client.ScreenMixin,pl:mixin:APP:ae2.mixins.json:WrappedGenericStackTooltipModIdMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.MouseHandler.m_91530_(MouseHandler.java:89) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:ldlib-common.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMouseHandler,pl:mixin:APP:balm.mixins.json:MouseHandlerAccessor,pl:mixin:APP:tacz.mixins.json:client.MouseHandlerMixin,pl:mixin:APP:mixins.cofhcore.json:MouseHandlerMixin,pl:mixin:APP:brewinandchewin.mixins.json:client.TipsyMouseHandlerMixin,pl:mixin:APP:create.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.MouseHandler.m_168091_(MouseHandler.java:189) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:ldlib-common.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMouseHandler,pl:mixin:APP:balm.mixins.json:MouseHandlerAccessor,pl:mixin:APP:tacz.mixins.json:client.MouseHandlerMixin,pl:mixin:APP:mixins.cofhcore.json:MouseHandlerMixin,pl:mixin:APP:brewinandchewin.mixins.json:client.TipsyMouseHandlerMixin,pl:mixin:APP:create.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:102) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B}
	at net.minecraft.client.MouseHandler.m_91565_(MouseHandler.java:188) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:ldlib-common.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMouseHandler,pl:mixin:APP:balm.mixins.json:MouseHandlerAccessor,pl:mixin:APP:tacz.mixins.json:client.MouseHandlerMixin,pl:mixin:APP:mixins.cofhcore.json:MouseHandlerMixin,pl:mixin:APP:brewinandchewin.mixins.json:client.TipsyMouseHandlerMixin,pl:mixin:APP:create.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at org.lwjgl.glfw.GLFWMouseButtonCallbackI.callback(GLFWMouseButtonCallbackI.java:43) ~[lwjgl-glfw-3.3.1.jar%2386!/:build 7] {}
	at org.lwjgl.system.JNI.invokeV(Native Method) ~[lwjgl-3.3.1.jar%2398!/:build 7] {}
	at org.lwjgl.glfw.GLFW.glfwWaitEventsTimeout(GLFW.java:3474) ~[lwjgl-glfw-3.3.1.jar%2386!/:build 7] {re:mixin}
-- Affected screen --
Details:
	Screen name: net.minecraft.client.gui.screens.TitleScreen
Stacktrace:
	at net.minecraft.client.gui.screens.Screen.m_96579_(Screen.java:437) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:computing_frames,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:aether.mixins.json:client.accessor.ScreenAccessor,pl:mixin:APP:balm.mixins.json:ScreenAccessor,pl:mixin:APP:patchouli_xplat.mixins.json:client.AccessorScreen,pl:mixin:APP:cumulus_menus.mixins.json:client.accessor.ScreenAccessor,pl:mixin:APP:quark.mixins.json:client.ScreenMixin,pl:mixin:APP:ae2.mixins.json:WrappedGenericStackTooltipModIdMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.MouseHandler.m_91530_(MouseHandler.java:89) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:ldlib-common.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMouseHandler,pl:mixin:APP:balm.mixins.json:MouseHandlerAccessor,pl:mixin:APP:tacz.mixins.json:client.MouseHandlerMixin,pl:mixin:APP:mixins.cofhcore.json:MouseHandlerMixin,pl:mixin:APP:brewinandchewin.mixins.json:client.TipsyMouseHandlerMixin,pl:mixin:APP:create.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.MouseHandler.m_168091_(MouseHandler.java:189) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:ldlib-common.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMouseHandler,pl:mixin:APP:balm.mixins.json:MouseHandlerAccessor,pl:mixin:APP:tacz.mixins.json:client.MouseHandlerMixin,pl:mixin:APP:mixins.cofhcore.json:MouseHandlerMixin,pl:mixin:APP:brewinandchewin.mixins.json:client.TipsyMouseHandlerMixin,pl:mixin:APP:create.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:102) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B}
	at net.minecraft.client.MouseHandler.m_91565_(MouseHandler.java:188) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:ldlib-common.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMouseHandler,pl:mixin:APP:balm.mixins.json:MouseHandlerAccessor,pl:mixin:APP:tacz.mixins.json:client.MouseHandlerMixin,pl:mixin:APP:mixins.cofhcore.json:MouseHandlerMixin,pl:mixin:APP:brewinandchewin.mixins.json:client.TipsyMouseHandlerMixin,pl:mixin:APP:create.mixins.json:accessor.MouseHandlerAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at org.lwjgl.glfw.GLFWMouseButtonCallbackI.callback(GLFWMouseButtonCallbackI.java:43) ~[lwjgl-glfw-3.3.1.jar%2386!/:build 7] {}
	at org.lwjgl.system.JNI.invokeV(Native Method) ~[lwjgl-3.3.1.jar%2398!/:build 7] {}
	at org.lwjgl.glfw.GLFW.glfwWaitEventsTimeout(GLFW.java:3474) ~[lwjgl-glfw-3.3.1.jar%2386!/:build 7] {re:mixin}
	at com.mojang.blaze3d.systems.RenderSystem.limitDisplayFPS(RenderSystem.java:237) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:flywheel.mixins.json:RenderTexturesMixin,pl:mixin:APP:embeddium.mixins.json:workarounds.event_loop.RenderSystemMixin,pl:mixin:A}
	at net.minecraft.client.Minecraft.m_91383_(Minecraft.java:1173) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.sodiumextras.json:impl.fps.GpuUsageMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.dedicated_reload_executor.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.blast_search_trees.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.world_leaks.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.concurrency.MinecraftMixin,pl:mixin:APP:modernfix-forge.mixins.json:feature.measure_time.MinecraftMixin_Forge,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMinecraft,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:carryon.mixins.json:MinecraftMixin,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:mixins.codechickenlib.json:MinecraftMixin,pl:mixin:APP:tofucraft.mixins.json:client.MinecraftMixin,pl:mixin:APP:ae2.mixins.json:PickColorMixin,pl:mixin:APP:moonlight-common.mixins.json:MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:configuration.mixins.json:MinecraftMixin,pl:mixin:APP:flywheel.mixins.json:PausedPartialTickAccessor,pl:mixin:APP:quark.mixins.json:client.MinecraftMixin,pl:mixin:APP:mixins.irons_spellbooks.json:MinecraftMixin,pl:mixin:APP:immediatelyfast-common.mixins.json:core.MixinMinecraftClient,pl:mixin:APP:create.mixins.json:client.WindowResizeMixin,pl:mixin:APP:embeddium.mixins.json:core.MinecraftClientMixin,pl:mixin:APP:embeddium.mixins.json:core.render.MinecraftAccessor,pl:mixin:APP:modernfix-common.mixins.json:feature.remove_telemetry.MinecraftMixin_Telemetry,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:718) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.sodiumextras.json:impl.fps.GpuUsageMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.dedicated_reload_executor.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.blast_search_trees.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.world_leaks.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.concurrency.MinecraftMixin,pl:mixin:APP:modernfix-forge.mixins.json:feature.measure_time.MinecraftMixin_Forge,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMinecraft,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:carryon.mixins.json:MinecraftMixin,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:mixins.codechickenlib.json:MinecraftMixin,pl:mixin:APP:tofucraft.mixins.json:client.MinecraftMixin,pl:mixin:APP:ae2.mixins.json:PickColorMixin,pl:mixin:APP:moonlight-common.mixins.json:MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:configuration.mixins.json:MinecraftMixin,pl:mixin:APP:flywheel.mixins.json:PausedPartialTickAccessor,pl:mixin:APP:quark.mixins.json:client.MinecraftMixin,pl:mixin:APP:mixins.irons_spellbooks.json:MinecraftMixin,pl:mixin:APP:immediatelyfast-common.mixins.json:core.MixinMinecraftClient,pl:mixin:APP:create.mixins.json:client.WindowResizeMixin,pl:mixin:APP:embeddium.mixins.json:core.MinecraftClientMixin,pl:mixin:APP:embeddium.mixins.json:core.render.MinecraftAccessor,pl:mixin:APP:modernfix-common.mixins.json:feature.remove_telemetry.MinecraftMixin_Telemetry,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:218) ~[minecraft-1.20.1-client.jar:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:flywheel.mixins.json:ClientMainMixin,pl:mixin:APP:cryonicconfig.mixins.json:client.MainMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:569) ~[?:?] {re:mixin}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:111) ~[fmlloader-1.20.1-47.4.0.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:99) ~[fmlloader-1.20.1-47.4.0.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$makeService$0(CommonClientLaunchHandler.java:25) ~[fmlloader-1.20.1-47.4.0.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:108) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:78) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:569) ~[?:?] {re:mixin}
	at io.github.zekerzhayard.forgewrapper.installer.Main.main(Main.java:67) ~[?:?] {}
	at org.prismlauncher.launcher.impl.StandardLauncher.launch(StandardLauncher.java:105) ~[?:?] {}
	at org.prismlauncher.EntryPoint.listen(EntryPoint.java:129) ~[?:?] {}
	at org.prismlauncher.EntryPoint.main(EntryPoint.java:70) ~[?:?] {}


-- Last reload --
Details:
	Reload number: 3
	Reload reason: manual
	Finished: Yes
	Packs: vanilla, tacz_resources, mod_resources, gtceu:dynamic_assets, gm_construct:dynamic_assets, Moonlight Mods Dynamic Assets
Stacktrace:
	at net.minecraft.client.ResourceLoadStateTracker.m_168562_(ResourceLoadStateTracker.java:49) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:classloading}
	at net.minecraft.client.Minecraft.m_91354_(Minecraft.java:2326) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.sodiumextras.json:impl.fps.GpuUsageMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.dedicated_reload_executor.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.blast_search_trees.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.world_leaks.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.concurrency.MinecraftMixin,pl:mixin:APP:modernfix-forge.mixins.json:feature.measure_time.MinecraftMixin_Forge,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMinecraft,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:carryon.mixins.json:MinecraftMixin,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:mixins.codechickenlib.json:MinecraftMixin,pl:mixin:APP:tofucraft.mixins.json:client.MinecraftMixin,pl:mixin:APP:ae2.mixins.json:PickColorMixin,pl:mixin:APP:moonlight-common.mixins.json:MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:configuration.mixins.json:MinecraftMixin,pl:mixin:APP:flywheel.mixins.json:PausedPartialTickAccessor,pl:mixin:APP:quark.mixins.json:client.MinecraftMixin,pl:mixin:APP:mixins.irons_spellbooks.json:MinecraftMixin,pl:mixin:APP:immediatelyfast-common.mixins.json:core.MixinMinecraftClient,pl:mixin:APP:create.mixins.json:client.WindowResizeMixin,pl:mixin:APP:embeddium.mixins.json:core.MinecraftClientMixin,pl:mixin:APP:embeddium.mixins.json:core.render.MinecraftAccessor,pl:mixin:APP:modernfix-common.mixins.json:feature.remove_telemetry.MinecraftMixin_Telemetry,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:735) ~[client-1.20.1-20230612.114412-srg.jar%23428!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.sodiumextras.json:impl.fps.GpuUsageMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.dedicated_reload_executor.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.blast_search_trees.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.world_leaks.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.concurrency.MinecraftMixin,pl:mixin:APP:modernfix-forge.mixins.json:feature.measure_time.MinecraftMixin_Forge,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMinecraft,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:carryon.mixins.json:MinecraftMixin,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:mixins.codechickenlib.json:MinecraftMixin,pl:mixin:APP:tofucraft.mixins.json:client.MinecraftMixin,pl:mixin:APP:ae2.mixins.json:PickColorMixin,pl:mixin:APP:moonlight-common.mixins.json:MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:configuration.mixins.json:MinecraftMixin,pl:mixin:APP:flywheel.mixins.json:PausedPartialTickAccessor,pl:mixin:APP:quark.mixins.json:client.MinecraftMixin,pl:mixin:APP:mixins.irons_spellbooks.json:MinecraftMixin,pl:mixin:APP:immediatelyfast-common.mixins.json:core.MixinMinecraftClient,pl:mixin:APP:create.mixins.json:client.WindowResizeMixin,pl:mixin:APP:embeddium.mixins.json:core.MinecraftClientMixin,pl:mixin:APP:embeddium.mixins.json:core.render.MinecraftAccessor,pl:mixin:APP:modernfix-common.mixins.json:feature.remove_telemetry.MinecraftMixin_Telemetry,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:218) ~[minecraft-1.20.1-client.jar:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:flywheel.mixins.json:ClientMainMixin,pl:mixin:APP:cryonicconfig.mixins.json:client.MainMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:569) ~[?:?] {re:mixin}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:111) ~[fmlloader-1.20.1-47.4.0.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:99) ~[fmlloader-1.20.1-47.4.0.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$makeService$0(CommonClientLaunchHandler.java:25) ~[fmlloader-1.20.1-47.4.0.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:108) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:78) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:569) ~[?:?] {re:mixin}
	at io.github.zekerzhayard.forgewrapper.installer.Main.main(Main.java:67) ~[?:?] {}
	at org.prismlauncher.launcher.impl.StandardLauncher.launch(StandardLauncher.java:105) ~[?:?] {}
	at org.prismlauncher.EntryPoint.listen(EntryPoint.java:129) ~[?:?] {}
	at org.prismlauncher.EntryPoint.main(EntryPoint.java:70) ~[?:?] {}


-- System Details --
Details:
	Minecraft Version: 1.20.1
	Minecraft Version ID: 1.20.1
	Operating System: Windows 11 (amd64) version 10.0
	Java Version: 17.0.15, Microsoft
	Java VM Version: OpenJDK 64-Bit Server VM (mixed mode), Microsoft
	Memory: 1594777664 bytes (1520 MiB) / 4294967296 bytes (4096 MiB) up to 4294967296 bytes (4096 MiB)
	CPUs: 16
	Processor Vendor: GenuineIntel
	Processor Name: Intel(R) Core(TM) i7-10700F CPU @ 2.90GHz
	Identifier: Intel64 Family 6 Model 165 Stepping 5
	Microarchitecture: unknown
	Frequency (GHz): 2.90
	Number of physical packages: 1
	Number of physical CPUs: 8
	Number of logical CPUs: 16
	Graphics card #0 name: NVIDIA GeForce RTX 3060 Ti
	Graphics card #0 vendor: NVIDIA (0x10de)
	Graphics card #0 VRAM (MB): 4095.00
	Graphics card #0 deviceId: 0x2486
	Graphics card #0 versionInfo: DriverVersion=32.0.15.7216
	Memory slot #0 capacity (MB): 16384.00
	Memory slot #0 clockSpeed (GHz): 2.67
	Memory slot #0 type: DDR4
	Memory slot #1 capacity (MB): 16384.00
	Memory slot #1 clockSpeed (GHz): 2.67
	Memory slot #1 type: DDR4
	Virtual memory max (MB): 38012.21
	Virtual memory used (MB): 33279.48
	Swap memory total (MB): 5376.00
	Swap memory used (MB): 146.04
	JVM Flags: 3 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xms512m -Xmx4096m
	Launched Version: 1.20.1
	Backend library: LWJGL version 3.3.1 build 7
	Backend API: NVIDIA GeForce RTX 3060 Ti/PCIe/SSE2 GL version 4.6.0 NVIDIA 572.16, NVIDIA Corporation
	Window size: 1920x1009
	GL Caps: Using framebuffer using OpenGL 3.2
	GL debug messages: 
	Using VBOs: Yes
	Is Modded: Definitely; Client brand changed to 'forge'
	Type: Client (map_client.txt)
	Graphics mode: fancy
	Resource Packs: 
	Current Language: en_us
	CPU: 16x Intel(R) Core(TM) i7-10700F CPU @ 2.90GHz
	ModLauncher: 10.0.9+10.0.9+main.dcd20f30
	ModLauncher launch target: forgeclient
	ModLauncher naming: srg
	ModLauncher services: 
		mixin-0.8.5.jar mixin PLUGINSERVICE 
		eventbus-6.0.5.jar eventbus PLUGINSERVICE 
		fmlloader-1.20.1-47.4.0.jar slf4jfixer PLUGINSERVICE 
		fmlloader-1.20.1-47.4.0.jar object_holder_definalize PLUGINSERVICE 
		fmlloader-1.20.1-47.4.0.jar runtime_enum_extender PLUGINSERVICE 
		fmlloader-1.20.1-47.4.0.jar capability_token_subclass PLUGINSERVICE 
		accesstransformers-8.0.4.jar accesstransformer PLUGINSERVICE 
		fmlloader-1.20.1-47.4.0.jar runtimedistcleaner PLUGINSERVICE 
		modlauncher-10.0.9.jar mixin TRANSFORMATIONSERVICE 
		modlauncher-10.0.9.jar fml TRANSFORMATIONSERVICE 
	FML Language Providers: 
		minecraft@1.0
		kotlinforforge@4.11.0
		javafml@null
		lowcodefml@null
	Mod List: 
		dungeons-and-taverns-pillager-outpost-rework-1.1 [|Dungeons and Taverns Pillager |mr_dungeons_andtavernspillager|1.1                 |DONE      |Manifest: NOSIGNATURE
		YungsBetterDungeons-1.20-Forge-4.0.4.jar          |YUNG's Better Dungeons        |betterdungeons                |1.20-Forge-4.0.4    |DONE      |Manifest: NOSIGNATURE
		kuma-api-forge-20.1.10+1.20.1.jar                 |KumaAPI                       |kuma_api                      |20.1.10             |DONE      |Manifest: NOSIGNATURE
		sodiumextras-forge-1.0.7-1.20.1.jar               |Sodium Extras                 |sodiumextras                  |1.0.6               |DONE      |Manifest: NOSIGNATURE
		geckolib-forge-1.20.1-4.7.1.3.jar                 |GeckoLib 4                    |geckolib                      |4.7.1.3             |DONE      |Manifest: NOSIGNATURE
		createdeco-2.0.2-1.20.1-forge.jar                 |Create Deco                   |createdeco                    |2.0.2-1.20.1-forge  |DONE      |Manifest: NOSIGNATURE
		player-animation-lib-forge-1.0.2-rc1+1.20.jar     |Player Animator               |playeranimator                |1.0.2-rc1+1.20      |DONE      |Manifest: NOSIGNATURE
		aether-1.20.1-1.5.2-neoforge.jar                  |The Aether                    |aether                        |1.20.1-1.5.2-neoforg|DONE      |Manifest: NOSIGNATURE
		TinkersLevellingAddon-1.20.1-1.4.3.jar            |Tinkers' Levelling Addon      |tinkerslevellingaddon         |1.4.3               |DONE      |Manifest: NOSIGNATURE
		ProjectE-1.20.1-PE1.0.1.jar                       |ProjectE                      |projecte                      |1.0.1               |DONE      |Manifest: NOSIGNATURE
		sophisticatedcore-1.20.1-1.2.12.872.jar           |Sophisticated Core            |sophisticatedcore             |1.2.12.872          |DONE      |Manifest: NOSIGNATURE
		structureessentials-1.20.1-4.7.jar                |Structure Essentials mod      |structureessentials           |1.20.1-4.7          |DONE      |Manifest: NOSIGNATURE
		creating_space_library-1.0.0.jar                  |creating space library        |creating_space_library        |1.0.0               |DONE      |Manifest: NOSIGNATURE
		ugoblock-1.20.1-beta1.1.0.jar                     |UgoBlock                      |ugoblock                      |1.20.1-beta1.1.0    |DONE      |Manifest: NOSIGNATURE
		Placebo-1.20.1-8.6.3.jar                          |Placebo                       |placebo                       |8.6.3               |DONE      |Manifest: NOSIGNATURE
		modernfix-forge-5.23.1+mc1.20.1.jar               |ModernFix                     |modernfix                     |5.23.1+mc1.20.1     |DONE      |Manifest: NOSIGNATURE
		YungsApi-1.20-Forge-4.0.6.jar                     |YUNG's API                    |yungsapi                      |1.20-Forge-4.0.6    |DONE      |Manifest: NOSIGNATURE
		bagus_lib-1.20.1-5.3.0.jar                        |Bagus Lib                     |bagus_lib                     |1.20.1-5.3.0        |DONE      |Manifest: NOSIGNATURE
		mixinextras-forge-0.4.1.jar                       |MixinExtras                   |mixinextras                   |0.4.1               |DONE      |Manifest: NOSIGNATURE
		sophisticatedbackpacks-1.20.1-3.23.5.1200.jar     |Sophisticated Backpacks       |sophisticatedbackpacks        |3.23.5.1200         |DONE      |Manifest: NOSIGNATURE
		CreateNumismatics-1.0.11+forge-mc1.20.1.jar       |Create: Numismatics           |numismatics                   |1.0.11+forge-mc1.20.|DONE      |Manifest: NOSIGNATURE
		create_dragon_lib-1.20.1-1.4.3.jar                |Create: Dragon Lib            |create_dragon_lib             |1.4.3               |DONE      |Manifest: NOSIGNATURE
		createdieselgenerators-1.20.1-1.2i.jar            |Create Diesel Generators      |createdieselgenerators        |1.20.1-1.2i         |DONE      |Manifest: NOSIGNATURE
		ldlib-forge-1.20.1-1.0.34.jar                     |LowDragLib                    |ldlib                         |1.0.34              |DONE      |Manifest: NOSIGNATURE
		Steam_Rails-1.6.7+forge-mc1.20.1.jar              |Create: Steam 'n' Rails       |railways                      |1.6.7+forge-mc1.20.1|DONE      |Manifest: NOSIGNATURE
		balm-forge-1.20.1-7.3.31-all.jar                  |Balm                          |balm                          |7.3.31              |DONE      |Manifest: NOSIGNATURE
		carryon-forge-1.20.1-2.1.2.7.jar                  |Carry On                      |carryon                       |2.1.2.7             |DONE      |Manifest: NOSIGNATURE
		sodiumoptionsapi-forge-1.0.10-1.20.1.jar          |Sodium Options API            |sodiumoptionsapi              |1.0.10              |DONE      |Manifest: NOSIGNATURE
		JustEnoughResources-1.20.1-1.4.0.247.jar          |Just Enough Resources         |jeresources                   |1.4.0.247           |DONE      |Manifest: NOSIGNATURE
		chat_heads-0.13.18-forge-1.20.jar                 |Chat Heads                    |chat_heads                    |0.13.18             |DONE      |Manifest: NOSIGNATURE
		interiors-0.5.6+forge-mc1.20.1-build.104.jar      |Create: Interiors             |interiors                     |0.5.6               |DONE      |Manifest: NOSIGNATURE
		cloth-config-11.1.136-forge.jar                   |Cloth Config v10 API          |cloth_config                  |11.1.136            |DONE      |Manifest: NOSIGNATURE
		dummmmmmy-1.20-2.0.7.jar                          |MmmMmmMmmmmm                  |dummmmmmy                     |1.20-2.0.7          |DONE      |Manifest: NOSIGNATURE
		twilightforest-1.20.1-4.3.2508-universal.jar      |The Twilight Forest           |twilightforest                |4.3.2508            |DONE      |Manifest: NOSIGNATURE
		refinedstorage-1.12.4.jar                         |Refined Storage               |refinedstorage                |1.12.4              |DONE      |Manifest: NOSIGNATURE
		embeddium-0.3.31+mc1.20.1.jar                     |Embeddium                     |embeddium                     |0.3.31+mc1.20.1     |DONE      |Manifest: NOSIGNATURE
		athena-forge-1.20.1-3.1.2.jar                     |Athena                        |athena                        |3.1.2               |DONE      |Manifest: NOSIGNATURE
		structure_gel-1.20.1-2.16.2.jar                   |Structure Gel API             |structure_gel                 |2.16.2              |DONE      |Manifest: NOSIGNATURE
		corpse-forge-1.20.1-1.0.21.jar                    |Corpse                        |corpse                        |1.20.1-1.0.21       |DONE      |Manifest: NOSIGNATURE
		chipped-forge-1.20.1-3.0.7.jar                    |Chipped                       |chipped                       |3.0.7               |DONE      |Manifest: NOSIGNATURE
		industrial-foregoing-1.20.1-3.5.19.jar            |Industrial Foregoing          |industrialforegoing           |3.5.19              |DONE      |Manifest: NOSIGNATURE
		FarmersDelight-1.20.1-1.2.8.jar                   |Farmer's Delight              |farmersdelight                |1.20.1-1.2.8        |DONE      |Manifest: NOSIGNATURE
		ends_delight-1.20.1-2.4.jar                       |End's Delight                 |ends_delight                  |2.4                 |DONE      |Manifest: NOSIGNATURE
		chefs-delight-1.0.3-forge-1.20.1.jar              |Chefs Delight                 |chefsdelight                  |1.0.3-forge-1.20.1  |DONE      |Manifest: NOSIGNATURE
		dungeons-and-taverns-stronghold-rework-1 [Forge].j|Dungeons and Taverns Stronghol|mr_dungeons_andtavernsstrongho|1                   |DONE      |Manifest: NOSIGNATURE
		tofucreate-1.20.1-0.2.1.jar                       |TofuCreate                    |tofucreate                    |1.20.1-0.2.1        |DONE      |Manifest: NOSIGNATURE
		dungeons_enhanced-1.20.1-5.4.2.jar                |Dungeons Enhanced             |dungeons_enhanced             |5.4.2               |DONE      |Manifest: NOSIGNATURE
		curios-forge-5.14.1+1.20.1.jar                    |Curios API                    |curios                        |5.14.1+1.20.1       |DONE      |Manifest: NOSIGNATURE
		Patchouli-1.20.1-84.1-FORGE.jar                   |Patchouli                     |patchouli                     |1.20.1-84.1-FORGE   |DONE      |Manifest: NOSIGNATURE
		oreexcavation-1.13.174.jar                        |OreExcavation                 |oreexcavation                 |1.13.174            |DONE      |Manifest: NOSIGNATURE
		dungeons-and-taverns-3.0.3.f[Forge].jar           |Dungeons and Taverns          |mr_dungeons_andtaverns        |3.0.3.f             |DONE      |Manifest: NOSIGNATURE
		ApothicAttributes-1.20.1-1.3.7.jar                |Apothic Attributes            |attributeslib                 |1.3.7               |DONE      |Manifest: NOSIGNATURE
		littlejoys-forge-1.20.1-20.1.8.jar                |Little Joys                   |littlejoys                    |20.1.8              |DONE      |Manifest: NOSIGNATURE
		resourcefullib-forge-1.20.1-2.1.29.jar            |Resourceful Lib               |resourcefullib                |2.1.29              |DONE      |Manifest: NOSIGNATURE
		cumulus_menus-1.20.1-1.0.1-neoforge.jar           |Cumulus                       |cumulus_menus                 |1.20.1-1.0.1-neoforg|DONE      |Manifest: NOSIGNATURE
		ProjectExtended-1.20.1-1.5.0.jar                  |ProjectExtended               |projectextended               |1.5.0               |DONE      |Manifest: NOSIGNATURE
		twilightdelight-2.0.15.jar                        |Twilight's Flavor & Delight   |twilightdelight               |2.0.15              |DONE      |Manifest: NOSIGNATURE
		architectury-9.2.14-forge.jar                     |Architectury                  |architectury                  |9.2.14              |DONE      |Manifest: NOSIGNATURE
		cupboard-1.20.1-2.7.jar                           |Cupboard utilities            |cupboard                      |1.20.1-2.7          |DONE      |Manifest: NOSIGNATURE
		nitrogen_internals-1.20.1-1.0.12-neoforge.jar     |Nitrogen                      |nitrogen_internals            |1.20.1-1.0.12-neofor|DONE      |Manifest: NOSIGNATURE
		l2library-2.4.16-slim.jar                         |L2 Library                    |l2library                     |2.4.16              |DONE      |Manifest: NOSIGNATURE
		CodeChickenLib-1.20.1-4.4.0.516-universal.jar     |CodeChicken Lib               |codechickenlib                |4.4.0.516           |DONE      |Manifest: 31:e6:db:63:47:4a:6e:e0:0a:2c:11:d1:76:db:4e:82:ff:56:2d:29:93:d2:e5:02:bd:d3:bd:9d:27:47:a5:71
		CBMultipart-1.20.1-3.3.0.146-universal.jar        |CBMultipart                   |cb_multipart                  |3.3.0.146           |DONE      |Manifest: NOSIGNATURE
		ProjectRed-1.20.1-4.21.0-core.jar                 |ProjectRed Core               |projectred_core               |4.21.0              |DONE      |Manifest: NOSIGNATURE
		ProjectRed-1.20.1-4.21.0-integration.jar          |ProjectRed Integration        |projectred_integration        |4.21.0              |DONE      |Manifest: NOSIGNATURE
		ProjectRed-1.20.1-4.21.0-expansion.jar            |ProjectRed Expansion          |projectred_expansion          |4.21.0              |DONE      |Manifest: NOSIGNATURE
		TofuCraftReload-1.20.1-5.16.1.0.jar               |TofuCraftReload               |tofucraft                     |1.20.1-5.16.1.0     |DONE      |Manifest: NOSIGNATURE
		tofudelight-1.20.1-3.2.0.jar                      |TofuDelight                   |tofudelight                   |1.20.1-3.2.0        |DONE      |Manifest: NOSIGNATURE
		quark_delight_1.0.0_forge_1.20.1.jar              |Quark Delight                 |quarkdelight                  |1.0.0               |DONE      |Manifest: NOSIGNATURE
		sliceanddice-forge-3.3.0.jar                      |Create Slice & Dice           |sliceanddice                  |3.3.0               |DONE      |Manifest: NOSIGNATURE
		creatingspace-1.20.1_1.7.9.jar                    |Creating Space                |creatingspace                 |1.20.1_1.7.9        |DONE      |Manifest: NOSIGNATURE
		culturaldelights-0.16.4.jar                       |Cultural Delights             |culturaldelights              |0.16.4              |DONE      |Manifest: NOSIGNATURE
		sophisticatedstorage-1.20.1-1.3.9.1075.jar        |Sophisticated Storage         |sophisticatedstorage          |1.3.9.1075          |DONE      |Manifest: NOSIGNATURE
		copycats-2.2.2+mc.1.20.1-forge.jar                |Create: Copycats+             |copycats                      |2.2.2+mc.1.20.1-forg|DONE      |Manifest: NOSIGNATURE
		jei-1.20.1-forge-15.20.0.106.jar                  |Just Enough Items             |jei                           |15.20.0.106         |DONE      |Manifest: NOSIGNATURE
		wood_enjoyer-forge-1.20-1.1.2.jar                 |Wood Enjoyer                  |wood_enjoyer                  |1.1.2               |DONE      |Manifest: NOSIGNATURE
		tacz-1.20.1-1.1.6.jar                             |Timeless & Classics Guns: Zero|tacz                          |1.1.6               |DONE      |Manifest: NOSIGNATURE
		Mekanism-1.20.1-10.4.16.80.jar                    |Mekanism                      |mekanism                      |10.4.16             |DONE      |Manifest: NOSIGNATURE
		MekanismGenerators-1.20.1-10.4.16.80.jar          |Mekanism: Generators          |mekanismgenerators            |10.4.16             |DONE      |Manifest: NOSIGNATURE
		MekanismAdditions-1.20.1-10.4.16.80.jar           |Mekanism: Additions           |mekanismadditions             |10.4.16             |DONE      |Manifest: NOSIGNATURE
		MekanismTools-1.20.1-10.4.16.80.jar               |Mekanism: Tools               |mekanismtools                 |10.4.16             |DONE      |Manifest: NOSIGNATURE
		caelus-forge-3.2.0+1.20.1.jar                     |Caelus API                    |caelus                        |3.2.0+1.20.1        |DONE      |Manifest: NOSIGNATURE
		journeymap-1.20.1-5.10.3-forge.jar                |Journeymap                    |journeymap                    |5.10.3              |DONE      |Manifest: NOSIGNATURE
		mcjtylib-1.20-8.0.7.jar                           |McJtyLib                      |mcjtylib                      |1.20-8.0.7          |DONE      |Manifest: NOSIGNATURE
		rftoolsbase-1.20-5.0.6.jar                        |RFToolsBase                   |rftoolsbase                   |1.20-5.0.6          |DONE      |Manifest: NOSIGNATURE
		rftoolsstorage-1.20-5.0.3.jar                     |RFToolsStorage                |rftoolsstorage                |1.20-5.0.3          |DONE      |Manifest: NOSIGNATURE
		rftoolscontrol-1.20-7.0.3.jar                     |RFToolsControl                |rftoolscontrol                |1.20-7.0.3          |DONE      |Manifest: NOSIGNATURE
		rftoolsdim-1.20-11.0.10.jar                       |RFToolsDimensions             |rftoolsdim                    |1.20-11.0.10        |DONE      |Manifest: NOSIGNATURE
		guideme-20.1.8.jar                                |GuideME                       |guideme                       |20.1.8              |DONE      |Manifest: NOSIGNATURE
		appliedenergistics2-forge-15.4.5.jar              |Applied Energistics 2         |ae2                           |15.4.5              |DONE      |Manifest: NOSIGNATURE
		sophisticatedinjections-1.0.1.jar                 |Sophisticated Injections      |sophisticatedinjections       |1.0.1               |DONE      |Manifest: NOSIGNATURE
		rftoolspower-1.20-6.0.2.jar                       |RFToolsPower                  |rftoolspower                  |1.20-6.0.2          |DONE      |Manifest: NOSIGNATURE
		forge-1.20.1-47.4.0-universal.jar                 |Forge                         |forge                         |47.4.0              |DONE      |Manifest: 84:ce:76:e8:45:35:e4:0e:63:86:df:47:59:80:0f:67:6c:c1:5f:6e:5f:4d:b3:54:47:1a:9f:7f:ed:5e:f2:90
		tfmg-0.9.3-1.20.1.jar                             |Create: The Factory Must Grow |tfmg                          |0.9.3-1.20.1        |DONE      |Manifest: NOSIGNATURE
		BrandonsCore-1.20.1-3.2.1.302-universal.jar       |Brandon's Core                |brandonscore                  |3.2.1.302           |DONE      |Manifest: 53:bb:a0:11:bd:61:e2:1a:e2:cb:fd:f8:4f:e4:cd:a5:cc:12:f4:43:f0:78:68:3b:e1:62:c6:78:3b:27:ff:fe
		Draconic-Evolution-1.20.1-3.1.2.604-universal.jar |Draconic Evolution            |draconicevolution             |3.1.2.604           |DONE      |Manifest: 53:bb:a0:11:bd:61:e2:1a:e2:cb:fd:f8:4f:e4:cd:a5:cc:12:f4:43:f0:78:68:3b:e1:62:c6:78:3b:27:ff:fe
		ironchest-1.20.1-14.4.4.jar                       |Iron Chests                   |ironchest                     |1.20.1-14.4.4       |DONE      |Manifest: NOSIGNATURE
		client-1.20.1-20230612.114412-srg.jar             |Minecraft                     |minecraft                     |1.20.1              |DONE      |Manifest: a1:d4:5e:04:4f:d3:d6:e0:7b:37:97:cf:77:b0:de:ad:4a:47:ce:8c:96:49:5f:0a:cf:8c:ae:b2:6d:4b:8a:3f
		cofh_core-1.20.1-11.0.2.56.jar                    |CoFH Core                     |cofh_core                     |11.0.2              |DONE      |Manifest: NOSIGNATURE
		thermal_core-1.20.1-11.0.6.24.jar                 |Thermal Series                |thermal                       |11.0.6              |DONE      |Manifest: NOSIGNATURE
		thermal_integration-1.20.1-11.0.1.27.jar          |Thermal Integration           |thermal_integration           |11.0.1              |DONE      |Manifest: NOSIGNATURE
		thermal_innovation-1.20.1-11.0.1.23.jar           |Thermal Innovation            |thermal_innovation            |11.0.1              |DONE      |Manifest: NOSIGNATURE
		thermal_foundation-1.20.1-11.0.6.70.jar           |Thermal Foundation            |thermal_foundation            |11.0.6              |DONE      |Manifest: NOSIGNATURE
		thermal_expansion-1.20.1-11.0.1.29.jar            |Thermal Expansion             |thermal_expansion             |11.0.1              |DONE      |Manifest: NOSIGNATURE
		thermal_dynamics-1.20.1-11.0.1.23.jar             |Thermal Dynamics              |thermal_dynamics              |11.0.1              |DONE      |Manifest: NOSIGNATURE
		tinkersdelight-1.2.0-forge-1.20.1.jar             |Tinkers' Delight              |tinkersdelight                |1.2.0               |DONE      |Manifest: NOSIGNATURE
		TConstruct-1.20.1-3.10.1.76.jar                   |Tinkers' Construct            |tconstruct                    |3.10.1.76           |DONE      |Manifest: NOSIGNATURE
		tinkersjewelry-1.2.0.jar                          |Tinkers' Jewelry              |tinkersjewelry                |1.2.0               |DONE      |Manifest: NOSIGNATURE
		rftoolsutility-1.20-6.0.6.jar                     |RFToolsUtility                |rftoolsutility                |1.20-6.0.6          |DONE      |Manifest: NOSIGNATURE
		simplyswords-forge-1.56.0-1.20.1.jar              |Simply Swords                 |simplyswords                  |1.56.0-1.20.1       |DONE      |Manifest: NOSIGNATURE
		moonlight-1.20-2.14.4-forge.jar                   |Moonlight Library             |moonlight                     |1.20-2.14.4         |DONE      |Manifest: NOSIGNATURE
		fabric-api-base-0.4.31+ef105b4977.jar             |Fabric API Base               |fabric_api_base               |0.4.31+ef105b4977   |DONE      |Manifest: NOSIGNATURE
		bettercombat-forge-1.8.6+1.20.1.jar               |Better Combat                 |bettercombat                  |1.8.6+1.20.1        |DONE      |Manifest: NOSIGNATURE
		configuration-forge-1.20.1-2.2.0.jar              |Configuration                 |configuration                 |2.2.0               |DONE      |Manifest: NOSIGNATURE
		gtceu-1.20.1-1.6.4.jar                            |GregTech                      |gtceu                         |1.6.4               |DONE      |Manifest: NOSIGNATURE
		gm_construct-1.0.5.jar                            |Greg's Modern Construct       |gm_construct                  |1.0.5               |DONE      |Manifest: NOSIGNATURE
		titanium-1.20.1-3.8.32.jar                        |Titanium                      |titanium                      |3.8.32              |DONE      |Manifest: NOSIGNATURE
		mysterious_mountain_lib-1.5.21-1.20.1.jar         |Mysterious Mountain Lib       |mysterious_mountain_lib       |1.5.21-1.20.1       |DONE      |Manifest: NOSIGNATURE
		corn_delight-1.1.6-1.20.1.jar                     |Corn Delight                  |corn_delight                  |1.1.6-1.20.1        |DONE      |Manifest: NOSIGNATURE
		spectrelib-forge-0.13.17+1.20.1.jar               |SpectreLib                    |spectrelib                    |0.13.17+1.20.1      |DONE      |Manifest: NOSIGNATURE
		nethersdelight-1.20.1-4.0.jar                     |Nether's Delight              |nethersdelight                |1.20.1-4.0          |DONE      |Manifest: NOSIGNATURE
		guccivuitton-1.20.1-0.2.2.jar                     |Gucci & Vuitton Attachments   |guccivuitton                  |0.2.2               |DONE      |Manifest: NOSIGNATURE
		EnderIO-1.20.1-6.2.10-beta-all.jar                |Ender IO                      |enderio                       |6.2.10-beta         |DONE      |Manifest: NOSIGNATURE
		kffmod-4.11.0.jar                                 |Kotlin For Forge              |kotlinforforge                |4.11.0              |DONE      |Manifest: NOSIGNATURE
		rftoolsbuilder-1.20-6.0.8.jar                     |RFToolsBuilder                |rftoolsbuilder                |1.20-6.0.8          |DONE      |Manifest: NOSIGNATURE
		BrewinAndChewin-1.20.1-3.2.1.jar                  |Brewin' And Chewin'           |brewinandchewin               |1.20.1-3.2.1        |DONE      |Manifest: NOSIGNATURE
		flywheel-forge-1.20.1-0.6.11-13.jar               |Flywheel                      |flywheel                      |0.6.11-13           |DONE      |Manifest: NOSIGNATURE
		create-1.20.1-0.5.1.j.jar                         |Create                        |create                        |0.5.1.j             |DONE      |Manifest: NOSIGNATURE
		extendedgears-2.1.1-1.20.1-0.5.1.f-forge.jar      |Extended Cogwheels            |extendedgears                 |2.1.1-1.20.1-0.5.1.f|DONE      |Manifest: NOSIGNATURE
		Mantle-1.20.1-1.11.61.jar                         |Mantle                        |mantle                        |1.11.61             |DONE      |Manifest: NOSIGNATURE
		polymorph-forge-0.49.10+1.20.1.jar                |Polymorph                     |polymorph                     |0.49.10+1.20.1      |DONE      |Manifest: NOSIGNATURE
		StorageDrawers-1.20.1-12.9.14.jar                 |Storage Drawers               |storagedrawers                |12.9.14             |DONE      |Manifest: NOSIGNATURE
		Zeta-1.0-30.jar                                   |Zeta                          |zeta                          |1.0-30              |DONE      |Manifest: NOSIGNATURE
		Quark-4.0-462.jar                                 |Quark                         |quark                         |4.0-462             |DONE      |Manifest: NOSIGNATURE
		infinitybuttons-1.20.1-4.0.7.jar                  |Infinity Buttons              |infinitybuttons               |1.20.1-4.0.7        |DONE      |Manifest: NOSIGNATURE
		irons_spellbooks-1.20.1-3.4.0.9.jar               |Iron's Spells 'n Spellbooks   |irons_spellbooks              |1.20.1-3.4.0.9      |DONE      |Manifest: NOSIGNATURE
		JustEnoughMekanismMultiblocks-1.20.1-4.10.jar     |Just Enough Mekanism Multibloc|jei_mekanism_multiblocks      |4.10                |DONE      |Manifest: NOSIGNATURE
		entityculling-forge-1.7.4-mc1.20.1.jar            |EntityCulling                 |entityculling                 |1.7.4               |DONE      |Manifest: NOSIGNATURE
		miners_delight-1.20.1-1.2.3.jar                   |Miner's Delight               |miners_delight                |1.20.1-1.2.3        |DONE      |Manifest: NOSIGNATURE
		cryonicconfig-forge-1.0.0+mc1.20.1.jar            |Cryonic Config                |cryonicconfig                 |1.0.0+mc1.20.1      |DONE      |Manifest: NOSIGNATURE
		ImmediatelyFast-Forge-1.5.0+1.20.4.jar            |ImmediatelyFast               |immediatelyfast               |1.5.0+1.20.4        |DONE      |Manifest: NOSIGNATURE
		oceansdelight-1.0.2-1.20.jar                      |Ocean's Delight               |oceansdelight                 |1.0.2-1.20          |DONE      |Manifest: NOSIGNATURE
		appleskin-forge-mc1.20.1-2.5.1.jar                |AppleSkin                     |appleskin                     |2.5.1+mc1.20.1      |DONE      |Manifest: NOSIGNATURE
		ferritecore-6.0.1-forge.jar                       |Ferrite Core                  |ferritecore                   |6.0.1               |DONE      |Manifest: 41:ce:50:66:d1:a0:05:ce:a1:0e:02:85:9b:46:64:e0:bf:2e:cf:60:30:9a:fe:0c:27:e0:63:66:9a:84:ce:8a
		chisel-forge-2.0.0+mc1.20.1.jar                   |Chisel Reborn                 |chisel                        |2.0.0+mc1.20.1      |DONE      |Manifest: NOSIGNATURE
		ProjectRed-1.20.1-4.21.0-illumination.jar         |ProjectRed Illumination       |projectred_illumination       |4.21.0              |DONE      |Manifest: NOSIGNATURE
		Delightful-1.20.1-3.7.2.jar                       |Delightful                    |delightful                    |3.7.2               |DONE      |Manifest: NOSIGNATURE
		cosmeticarmorreworked-1.20.1-v1a.jar              |CosmeticArmorReworked         |cosmeticarmorreworked         |1.20.1-v1a          |DONE      |Manifest: 5e:ed:25:99:e4:44:14:c0:dd:89:c1:a9:4c:10:b5:0d:e4:b1:52:50:45:82:13:d8:d0:32:89:67:56:57:01:53
		create_enchantment_industry-1.20.1-for-create-0.5.|Create Enchantment Industry   |create_enchantment_industry   |1.2.9.d             |DONE      |Manifest: NOSIGNATURE
		createaddition-1.20.1-1.2.5.jar                   |Create Crafts & Additions     |createaddition                |1.20.1-1.2.5        |DONE      |Manifest: NOSIGNATURE
	Crash Report UUID: cbef3474-ebe5-4489-80fe-be9624a2578b
	FML: 47.4
	Forge: net.minecraftforge:47.4.0
	Flywheel Backend: GL33 Instanced Arrays
