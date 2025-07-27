---- Minecraft Crash Report ----

// Hi. I'm Connector, and I'm a crashaholic
=========================
SINYTRA CONNECTOR IS PRESENT!
Please verify issues are not caused by Connector before reporting them to mod authors.
If you're unsure, file a report on Connector's issue tracker found at https://github.com/Sinytra/Connector/issues.
=========================

// Surprise! Haha. Well, this is awkward.

Time: 2025-07-27 23:28:27
Description: Initializing game

java.lang.NullPointerException: Initializing game
	at java.util.concurrent.ConcurrentHashMap.putVal(ConcurrentHashMap.java:1011) ~[?:?] {re:mixin}
	at java.util.concurrent.ConcurrentHashMap.put(ConcurrentHashMap.java:1006) ~[?:?] {re:mixin}
	at org.betterx.bclib.client.models.CustomModelBakery.addItemModel(CustomModelBakery.java:109) ~[bclib-3.0.14_mapped_srg_1.20.1.jar%231685!/:?] {re:classloading,re:mixin}
	at org.betterx.bclib.client.models.CustomModelBakery.lambda$loadCustomModels$1(CustomModelBakery.java:52) ~[bclib-3.0.14_mapped_srg_1.20.1.jar%231685!/:?] {re:classloading,re:mixin}
	at java.util.stream.ForEachOps$ForEachOp$OfRef.accept(ForEachOps.java:183) ~[?:?] {}
	at java.util.stream.ReferencePipeline$2$1.accept(ReferencePipeline.java:179) ~[?:?] {}
	at java.util.Spliterators$ArraySpliterator.forEachRemaining(Spliterators.java:992) ~[?:?] {}
	at java.util.stream.AbstractPipeline.copyInto(AbstractPipeline.java:509) ~[?:?] {}
	at java.util.stream.ForEachOps$ForEachTask.compute(ForEachOps.java:290) ~[?:?] {}
	at java.util.concurrent.CountedCompleter.exec(CountedCompleter.java:754) ~[?:?] {}
	at java.util.concurrent.ForkJoinTask.doExec(ForkJoinTask.java:373) ~[?:?] {}
	at java.util.concurrent.ForkJoinTask.invoke(ForkJoinTask.java:686) ~[?:?] {}
	at java.util.stream.ForEachOps$ForEachOp.evaluateParallel(ForEachOps.java:159) ~[?:?] {}
	at java.util.stream.ForEachOps$ForEachOp$OfRef.evaluateParallel(ForEachOps.java:173) ~[?:?] {}
	at java.util.stream.AbstractPipeline.evaluate(AbstractPipeline.java:233) ~[?:?] {}
	at java.util.stream.ReferencePipeline.forEach(ReferencePipeline.java:596) ~[?:?] {}
	at org.betterx.bclib.client.models.CustomModelBakery.loadCustomModels(CustomModelBakery.java:38) ~[bclib-3.0.14_mapped_srg_1.20.1.jar%231685!/:?] {re:classloading,re:mixin}
	at net.minecraft.client.resources.model.ModelManager.handler$fcn000$bclib$loadCustomModels(ModelManager.java:1530) ~[client-1.20.1-20230612.114412-srg.jar%23956!/:?] {re:mixin,pl:accesstransformer:B,pl:connector_pre_launch:A,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:connector_pre_launch:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.resources.model.ModelManager.m_5540_(ModelManager.java:78) ~[client-1.20.1-20230612.114412-srg.jar%23956!/:?] {re:mixin,pl:accesstransformer:B,pl:connector_pre_launch:A,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:connector_pre_launch:A,pl:runtimedistcleaner:A}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10827_(SimpleReloadInstance.java:32) ~[client-1.20.1-20230612.114412-srg.jar%23956!/:?] {re:mixin,pl:connector_pre_launch:A,re:classloading,pl:mixin:APP:fabric-resource-loader-v0.mixins.json:SimpleResourceReloadMixin from mod fabric_resource_loader_v0,pl:mixin:APP:emi_loot-common.mixins.json:SimpleResourceReloadMixin from mod emi_loot,pl:mixin:A,pl:connector_pre_launch:A}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.<init>(SimpleReloadInstance.java:44) ~[client-1.20.1-20230612.114412-srg.jar%23956!/:?] {re:mixin,pl:connector_pre_launch:A,re:classloading,pl:mixin:APP:fabric-resource-loader-v0.mixins.json:SimpleResourceReloadMixin from mod fabric_resource_loader_v0,pl:mixin:APP:emi_loot-common.mixins.json:SimpleResourceReloadMixin from mod emi_loot,pl:mixin:A,pl:connector_pre_launch:A}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10815_(SimpleReloadInstance.java:32) ~[client-1.20.1-20230612.114412-srg.jar%23956!/:?] {re:mixin,pl:connector_pre_launch:A,re:classloading,pl:mixin:APP:fabric-resource-loader-v0.mixins.json:SimpleResourceReloadMixin from mod fabric_resource_loader_v0,pl:mixin:APP:emi_loot-common.mixins.json:SimpleResourceReloadMixin from mod emi_loot,pl:mixin:A,pl:connector_pre_launch:A}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_203834_(SimpleReloadInstance.java:101) ~[client-1.20.1-20230612.114412-srg.jar%23956!/:?] {re:mixin,pl:connector_pre_launch:A,re:classloading,pl:mixin:APP:fabric-resource-loader-v0.mixins.json:SimpleResourceReloadMixin from mod fabric_resource_loader_v0,pl:mixin:APP:emi_loot-common.mixins.json:SimpleResourceReloadMixin from mod emi_loot,pl:mixin:A,pl:connector_pre_launch:A}
	at net.minecraft.server.packs.resources.ReloadableResourceManager.m_142463_(ReloadableResourceManager.java:45) ~[client-1.20.1-20230612.114412-srg.jar%23956!/:?] {re:mixin,pl:accesstransformer:B,pl:connector_pre_launch:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:modernfix-common.mixins.json:perf.resourcepacks.ReloadableResourceManagerMixin from mod modernfix,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.SimpleReloadableResourceManagerMixin from mod modernfix,pl:mixin:APP:fabric-resource-loader-v0.mixins.json:ReloadableResourceManagerImplMixin from mod fabric_resource_loader_v0,pl:mixin:A,pl:connector_pre_launch:A}
	at net.minecraft.client.Minecraft.<init>(Minecraft.java:561) ~[client-1.20.1-20230612.114412-srg.jar%23956!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:connector_pre_launch:A,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:mixin:APP:alexscaves.mixins.json:client.MinecraftMixin from mod alexscaves,pl:mixin:APP:owo.mixins.json:MinecraftClientMixin from mod owo,pl:mixin:APP:redirectionor.mixins.json:net.minecraft.client.MinecraftMixin from mod redirectionor,pl:mixin:APP:amecsapi.mixins.json:MixinMinecraftClient from mod amecsapi,pl:mixin:APP:connectorextras_architectury_bridge.mixins.json:MinecraftMixin from mod connectorextras_architectury_bridge,pl:mixin:APP:tofucraft.mixins.json:client.MinecraftMixin from mod tofucraft,pl:mixin:APP:azurelib.forge.mixins.json:MinecraftMixin from mod azurelib,pl:mixin:APP:the_bumblezone-common.mixins.json:client.MinecraftMixin from mod the_bumblezone,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor from mod bettercombat,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject from mod bettercombat,pl:mixin:APP:fancymenu.general.mixin.json:IMixinMinecraft from mod fancymenu,pl:mixin:APP:fancymenu.general.mixin.json:MixinMinecraft from mod fancymenu,pl:mixin:APP:fabric-screen-api-v1.mixins.json:MinecraftClientMixin from mod fabric_screen_api_v1,pl:mixin:APP:pickupnotifier.common.mixins.json:client.MinecraftMixin from mod pickupnotifier,pl:mixin:APP:iceberg.mixins.json:MinecraftMixin from mod iceberg,pl:mixin:APP:fallingleaves.mixins.json:MinecraftClientMixin from mod fallingleaves,pl:mixin:APP:mixins.connectorextras_modmenu_bridge.json:MinecraftMixin from mod connectorextras_modmenu_bridge,pl:mixin:APP:architectury.mixins.json:MixinMinecraft from mod architectury,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMinecraft from mod railways,pl:mixin:APP:fabric-lifecycle-events-v1.client.mixins.json:MinecraftClientMixin from mod fabric_lifecycle_events_v1,pl:mixin:APP:bookshelf.common.mixins.json:accessors.client.AccessorMinecraft from mod bookshelf,pl:mixin:APP:connectormod.mixins.json:registries.MinecraftMixin from mod connectormod,pl:mixin:APP:flywheel.impl.mixins.json:MinecraftMixin from mod flywheel,pl:mixin:APP:konkrete.mixin.json:MixinMinecraft from mod konkrete,pl:mixin:APP:balm.mixins.json:MinecraftMixin from mod balm,pl:mixin:APP:fabric-registry-sync-v0.client.mixins.json:MinecraftClientMixin from mod fabric_registry_sync_v0,pl:mixin:APP:ponder-common.mixins.json:client.WindowResizeMixin from mod ponder,pl:mixin:APP:resourcepackoverrides.common.mixins.json:client.MinecraftMixin from mod resourcepackoverrides,pl:mixin:APP:mixins/common/nochatreports.mixins.json:client.MixinMinecraft from mod nochatreports,pl:mixin:APP:nicer_skies.mixins.json:MinecraftMixin from mod nicer_skies,pl:mixin:APP:drippyloadingscreen.mixin.json:client.IMixinMinecraft from mod drippyloadingscreen,pl:mixin:APP:drippyloadingscreen.mixin.json:client.MixinMinecraft from mod drippyloadingscreen,pl:mixin:APP:ae2.mixins.json:PickColorMixin from mod ae2,pl:mixin:APP:modernfix-common.mixins.json:perf.blast_search_trees.MinecraftMixin from mod modernfix,pl:mixin:APP:modernfix-common.mixins.json:perf.dedicated_reload_executor.MinecraftMixin from mod modernfix,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.MinecraftMixin from mod modernfix,pl:mixin:APP:modernfix-common.mixins.json:bugfix.concurrency.MinecraftMixin from mod modernfix,pl:mixin:APP:modernfix-common.mixins.json:bugfix.world_leaks.MinecraftMixin from mod modernfix,pl:mixin:APP:modernfix-forge.mixins.json:feature.measure_time.MinecraftMixin_Forge from mod modernfix,pl:mixin:APP:exposure-common.mixins.json:MinecraftMixin from mod exposure,pl:mixin:APP:owo.mixins.json:ui.MinecraftClientMixin from mod owo,pl:mixin:APP:bclib.mixins.client.json:MinecraftMixin from mod bclib,pl:mixin:APP:ars_nouveau.mixins.json:light.ClientMixin from mod ars_nouveau,pl:mixin:APP:quark.mixins.json:client.MinecraftMixin from mod quark,pl:mixin:APP:botania_xplat.mixins.json:client.MinecraftAccessor from mod botania,pl:mixin:APP:fabric-events-interaction-v0.client.mixins.json:MinecraftClientMixin from mod fabric_events_interaction_v0,pl:mixin:APP:omega-config.mixins.json:ClientMixin from mod omega_config,pl:mixin:APP:spruceui.mixins.json:MinecraftClientMixin from mod spruceui,pl:mixin:APP:fabric-networking-api-v1.client.mixins.json:accessor.MinecraftClientAccessor from mod fabric_networking_api_v1,pl:mixin:APP:immersiveengineering.mixins.json:accessors.client.MinecraftAccess from mod immersiveengineering,pl:mixin:APP:reborncore.client.mixins.json:MixinMinecraftClient from mod reborncore,pl:mixin:APP:betterthirdperson.mixins.json:MinecraftMixin from mod betterthirdperson,pl:mixin:APP:carryon.mixins.json:MinecraftMixin from mod carryon,pl:mixin:APP:betterend.mixins.client.json:MinecraftClientMixin from mod betterend,pl:mixin:APP:entity_texture_features-common.mixins.json:reloading.MixinMinecraftClient from mod entity_texture_features,pl:mixin:APP:craterlib.mixins.json:events.client.MinecraftMixin from mod craterlib,pl:mixin:APP:biomemusic.mixins.json:ClientMusicChoiceMixin from mod biomemusic,pl:mixin:APP:entity_model_features-common.mixins.json:MixinResourceReload from mod entity_model_features,pl:mixin:APP:entity_model_features-common.mixins.json:accessor.MinecraftClientAccessor from mod entity_model_features,pl:mixin:APP:mixins.irons_spellbooks.json:MinecraftMixin from mod irons_spellbooks,pl:mixin:APP:xaeroplus.mixins.json:mc.MixinMinecraftClient from mod xaeroplus,pl:mixin:APP:emi.mixins.json:MinecraftClientMixin from mod emi,pl:mixin:APP:embeddium.mixins.json:core.MinecraftClientMixin from mod embeddium,pl:mixin:APP:embeddium.mixins.json:core.render.MinecraftAccessor from mod embeddium,pl:mixin:APP:securitycraft.mixins.json:camera.MinecraftMixin from mod securitycraft,pl:mixin:APP:ars_nouveau.mixins.json:camera.MinecraftMixin from mod ars_nouveau,pl:mixin:APP:forge-badoptimizations.mixins.json:MixinClient from mod (unknown),pl:mixin:APP:mixins.connectorextras_geckolib_fabric_compat.json:MinecraftMixin from mod connectorextras_geckolib_fabric_compat,pl:mixin:APP:connectormod.mixins.json:boot.MinecraftMixin from mod connectormod,pl:mixin:A,pl:connector_pre_launch:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:182) ~[minecraft-1.20.1-client.jar:?] {re:mixin,pl:connector_pre_launch:A,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:mixins.emibridge.json:MainEntrypointMixin from mod connectorextras_emi_bridge,pl:mixin:APP:cryonicconfig.mixins.json:client.MainMixin from mod cryonicconfig,pl:mixin:A,pl:connector_pre_launch:A,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:569) ~[?:?] {re:mixin}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:126) ~[loader-47.2.2.jar:47.2] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:114) ~[loader-47.2.2.jar:47.2] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.runService(CommonClientLaunchHandler.java:24) ~[loader-47.2.2.jar:47.2] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.lambda$launchService$4(CommonLaunchHandler.java:108) ~[loader-47.2.2.jar:47.2] {}
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
	at io.github.zekerzhayard.forgewrapper.installer.Main.main(Main.java:69) ~[?:?] {}
	at org.prismlauncher.launcher.impl.StandardLauncher.launch(StandardLauncher.java:105) ~[?:?] {}
	at org.prismlauncher.EntryPoint.listen(EntryPoint.java:129) ~[?:?] {}
	at org.prismlauncher.EntryPoint.main(EntryPoint.java:70) ~[?:?] {}


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Render thread
Stacktrace:
	at java.util.concurrent.ConcurrentHashMap.putVal(ConcurrentHashMap.java:1011) ~[?:?] {re:mixin}
	at java.util.concurrent.ConcurrentHashMap.put(ConcurrentHashMap.java:1006) ~[?:?] {re:mixin}
	at org.betterx.bclib.client.models.CustomModelBakery.addItemModel(CustomModelBakery.java:109) ~[bclib-3.0.14_mapped_srg_1.20.1.jar%231685!/:?] {re:classloading,re:mixin}
	at org.betterx.bclib.client.models.CustomModelBakery.lambda$loadCustomModels$1(CustomModelBakery.java:52) ~[bclib-3.0.14_mapped_srg_1.20.1.jar%231685!/:?] {re:classloading,re:mixin}
	at java.util.stream.ForEachOps$ForEachOp$OfRef.accept(ForEachOps.java:183) ~[?:?] {}
	at java.util.stream.ReferencePipeline$2$1.accept(ReferencePipeline.java:179) ~[?:?] {}
	at java.util.Spliterators$ArraySpliterator.forEachRemaining(Spliterators.java:992) ~[?:?] {}
	at java.util.stream.AbstractPipeline.copyInto(AbstractPipeline.java:509) ~[?:?] {}
	at java.util.stream.ForEachOps$ForEachTask.compute(ForEachOps.java:290) ~[?:?] {}
	at java.util.concurrent.CountedCompleter.exec(CountedCompleter.java:754) ~[?:?] {}
	at java.util.concurrent.ForkJoinTask.doExec(ForkJoinTask.java:373) ~[?:?] {}
	at java.util.concurrent.ForkJoinTask.invoke(ForkJoinTask.java:686) ~[?:?] {}
	at java.util.stream.ForEachOps$ForEachOp.evaluateParallel(ForEachOps.java:159) ~[?:?] {}
	at java.util.stream.ForEachOps$ForEachOp$OfRef.evaluateParallel(ForEachOps.java:173) ~[?:?] {}
	at java.util.stream.AbstractPipeline.evaluate(AbstractPipeline.java:233) ~[?:?] {}
	at java.util.stream.ReferencePipeline.forEach(ReferencePipeline.java:596) ~[?:?] {}
	at org.betterx.bclib.client.models.CustomModelBakery.loadCustomModels(CustomModelBakery.java:38) ~[bclib-3.0.14_mapped_srg_1.20.1.jar%231685!/:?] {re:classloading,re:mixin}
	at net.minecraft.client.resources.model.ModelManager.handler$fcn000$bclib$loadCustomModels(ModelManager.java:1530) ~[client-1.20.1-20230612.114412-srg.jar%23956!/:?] {re:mixin,pl:accesstransformer:B,pl:connector_pre_launch:A,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:connector_pre_launch:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.resources.model.ModelManager.m_5540_(ModelManager.java:78) ~[client-1.20.1-20230612.114412-srg.jar%23956!/:?] {re:mixin,pl:accesstransformer:B,pl:connector_pre_launch:A,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:connector_pre_launch:A,pl:runtimedistcleaner:A}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10827_(SimpleReloadInstance.java:32) ~[client-1.20.1-20230612.114412-srg.jar%23956!/:?] {re:mixin,pl:connector_pre_launch:A,re:classloading,pl:mixin:APP:fabric-resource-loader-v0.mixins.json:SimpleResourceReloadMixin from mod fabric_resource_loader_v0,pl:mixin:APP:emi_loot-common.mixins.json:SimpleResourceReloadMixin from mod emi_loot,pl:mixin:A,pl:connector_pre_launch:A}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.<init>(SimpleReloadInstance.java:44) ~[client-1.20.1-20230612.114412-srg.jar%23956!/:?] {re:mixin,pl:connector_pre_launch:A,re:classloading,pl:mixin:APP:fabric-resource-loader-v0.mixins.json:SimpleResourceReloadMixin from mod fabric_resource_loader_v0,pl:mixin:APP:emi_loot-common.mixins.json:SimpleResourceReloadMixin from mod emi_loot,pl:mixin:A,pl:connector_pre_launch:A}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10815_(SimpleReloadInstance.java:32) ~[client-1.20.1-20230612.114412-srg.jar%23956!/:?] {re:mixin,pl:connector_pre_launch:A,re:classloading,pl:mixin:APP:fabric-resource-loader-v0.mixins.json:SimpleResourceReloadMixin from mod fabric_resource_loader_v0,pl:mixin:APP:emi_loot-common.mixins.json:SimpleResourceReloadMixin from mod emi_loot,pl:mixin:A,pl:connector_pre_launch:A}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_203834_(SimpleReloadInstance.java:101) ~[client-1.20.1-20230612.114412-srg.jar%23956!/:?] {re:mixin,pl:connector_pre_launch:A,re:classloading,pl:mixin:APP:fabric-resource-loader-v0.mixins.json:SimpleResourceReloadMixin from mod fabric_resource_loader_v0,pl:mixin:APP:emi_loot-common.mixins.json:SimpleResourceReloadMixin from mod emi_loot,pl:mixin:A,pl:connector_pre_launch:A}
	at net.minecraft.server.packs.resources.ReloadableResourceManager.m_142463_(ReloadableResourceManager.java:45) ~[client-1.20.1-20230612.114412-srg.jar%23956!/:?] {re:mixin,pl:accesstransformer:B,pl:connector_pre_launch:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:modernfix-common.mixins.json:perf.resourcepacks.ReloadableResourceManagerMixin from mod modernfix,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.SimpleReloadableResourceManagerMixin from mod modernfix,pl:mixin:APP:fabric-resource-loader-v0.mixins.json:ReloadableResourceManagerImplMixin from mod fabric_resource_loader_v0,pl:mixin:A,pl:connector_pre_launch:A}
	at net.minecraft.client.Minecraft.<init>(Minecraft.java:561) ~[client-1.20.1-20230612.114412-srg.jar%23956!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:connector_pre_launch:A,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:mixin:APP:alexscaves.mixins.json:client.MinecraftMixin from mod alexscaves,pl:mixin:APP:owo.mixins.json:MinecraftClientMixin from mod owo,pl:mixin:APP:redirectionor.mixins.json:net.minecraft.client.MinecraftMixin from mod redirectionor,pl:mixin:APP:amecsapi.mixins.json:MixinMinecraftClient from mod amecsapi,pl:mixin:APP:connectorextras_architectury_bridge.mixins.json:MinecraftMixin from mod connectorextras_architectury_bridge,pl:mixin:APP:tofucraft.mixins.json:client.MinecraftMixin from mod tofucraft,pl:mixin:APP:azurelib.forge.mixins.json:MinecraftMixin from mod azurelib,pl:mixin:APP:the_bumblezone-common.mixins.json:client.MinecraftMixin from mod the_bumblezone,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor from mod bettercombat,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject from mod bettercombat,pl:mixin:APP:fancymenu.general.mixin.json:IMixinMinecraft from mod fancymenu,pl:mixin:APP:fancymenu.general.mixin.json:MixinMinecraft from mod fancymenu,pl:mixin:APP:fabric-screen-api-v1.mixins.json:MinecraftClientMixin from mod fabric_screen_api_v1,pl:mixin:APP:pickupnotifier.common.mixins.json:client.MinecraftMixin from mod pickupnotifier,pl:mixin:APP:iceberg.mixins.json:MinecraftMixin from mod iceberg,pl:mixin:APP:fallingleaves.mixins.json:MinecraftClientMixin from mod fallingleaves,pl:mixin:APP:mixins.connectorextras_modmenu_bridge.json:MinecraftMixin from mod connectorextras_modmenu_bridge,pl:mixin:APP:architectury.mixins.json:MixinMinecraft from mod architectury,pl:mixin:APP:railways-common.mixins.json:conductor_possession.MixinMinecraft from mod railways,pl:mixin:APP:fabric-lifecycle-events-v1.client.mixins.json:MinecraftClientMixin from mod fabric_lifecycle_events_v1,pl:mixin:APP:bookshelf.common.mixins.json:accessors.client.AccessorMinecraft from mod bookshelf,pl:mixin:APP:connectormod.mixins.json:registries.MinecraftMixin from mod connectormod,pl:mixin:APP:flywheel.impl.mixins.json:MinecraftMixin from mod flywheel,pl:mixin:APP:konkrete.mixin.json:MixinMinecraft from mod konkrete,pl:mixin:APP:balm.mixins.json:MinecraftMixin from mod balm,pl:mixin:APP:fabric-registry-sync-v0.client.mixins.json:MinecraftClientMixin from mod fabric_registry_sync_v0,pl:mixin:APP:ponder-common.mixins.json:client.WindowResizeMixin from mod ponder,pl:mixin:APP:resourcepackoverrides.common.mixins.json:client.MinecraftMixin from mod resourcepackoverrides,pl:mixin:APP:mixins/common/nochatreports.mixins.json:client.MixinMinecraft from mod nochatreports,pl:mixin:APP:nicer_skies.mixins.json:MinecraftMixin from mod nicer_skies,pl:mixin:APP:drippyloadingscreen.mixin.json:client.IMixinMinecraft from mod drippyloadingscreen,pl:mixin:APP:drippyloadingscreen.mixin.json:client.MixinMinecraft from mod drippyloadingscreen,pl:mixin:APP:ae2.mixins.json:PickColorMixin from mod ae2,pl:mixin:APP:modernfix-common.mixins.json:perf.blast_search_trees.MinecraftMixin from mod modernfix,pl:mixin:APP:modernfix-common.mixins.json:perf.dedicated_reload_executor.MinecraftMixin from mod modernfix,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.MinecraftMixin from mod modernfix,pl:mixin:APP:modernfix-common.mixins.json:bugfix.concurrency.MinecraftMixin from mod modernfix,pl:mixin:APP:modernfix-common.mixins.json:bugfix.world_leaks.MinecraftMixin from mod modernfix,pl:mixin:APP:modernfix-forge.mixins.json:feature.measure_time.MinecraftMixin_Forge from mod modernfix,pl:mixin:APP:exposure-common.mixins.json:MinecraftMixin from mod exposure,pl:mixin:APP:owo.mixins.json:ui.MinecraftClientMixin from mod owo,pl:mixin:APP:bclib.mixins.client.json:MinecraftMixin from mod bclib,pl:mixin:APP:ars_nouveau.mixins.json:light.ClientMixin from mod ars_nouveau,pl:mixin:APP:quark.mixins.json:client.MinecraftMixin from mod quark,pl:mixin:APP:botania_xplat.mixins.json:client.MinecraftAccessor from mod botania,pl:mixin:APP:fabric-events-interaction-v0.client.mixins.json:MinecraftClientMixin from mod fabric_events_interaction_v0,pl:mixin:APP:omega-config.mixins.json:ClientMixin from mod omega_config,pl:mixin:APP:spruceui.mixins.json:MinecraftClientMixin from mod spruceui,pl:mixin:APP:fabric-networking-api-v1.client.mixins.json:accessor.MinecraftClientAccessor from mod fabric_networking_api_v1,pl:mixin:APP:immersiveengineering.mixins.json:accessors.client.MinecraftAccess from mod immersiveengineering,pl:mixin:APP:reborncore.client.mixins.json:MixinMinecraftClient from mod reborncore,pl:mixin:APP:betterthirdperson.mixins.json:MinecraftMixin from mod betterthirdperson,pl:mixin:APP:carryon.mixins.json:MinecraftMixin from mod carryon,pl:mixin:APP:betterend.mixins.client.json:MinecraftClientMixin from mod betterend,pl:mixin:APP:entity_texture_features-common.mixins.json:reloading.MixinMinecraftClient from mod entity_texture_features,pl:mixin:APP:craterlib.mixins.json:events.client.MinecraftMixin from mod craterlib,pl:mixin:APP:biomemusic.mixins.json:ClientMusicChoiceMixin from mod biomemusic,pl:mixin:APP:entity_model_features-common.mixins.json:MixinResourceReload from mod entity_model_features,pl:mixin:APP:entity_model_features-common.mixins.json:accessor.MinecraftClientAccessor from mod entity_model_features,pl:mixin:APP:mixins.irons_spellbooks.json:MinecraftMixin from mod irons_spellbooks,pl:mixin:APP:xaeroplus.mixins.json:mc.MixinMinecraftClient from mod xaeroplus,pl:mixin:APP:emi.mixins.json:MinecraftClientMixin from mod emi,pl:mixin:APP:embeddium.mixins.json:core.MinecraftClientMixin from mod embeddium,pl:mixin:APP:embeddium.mixins.json:core.render.MinecraftAccessor from mod embeddium,pl:mixin:APP:securitycraft.mixins.json:camera.MinecraftMixin from mod securitycraft,pl:mixin:APP:ars_nouveau.mixins.json:camera.MinecraftMixin from mod ars_nouveau,pl:mixin:APP:forge-badoptimizations.mixins.json:MixinClient from mod (unknown),pl:mixin:APP:mixins.connectorextras_geckolib_fabric_compat.json:MinecraftMixin from mod connectorextras_geckolib_fabric_compat,pl:mixin:APP:connectormod.mixins.json:boot.MinecraftMixin from mod connectormod,pl:mixin:A,pl:connector_pre_launch:A,pl:runtimedistcleaner:A}
Mixins in Heaven:
	net.minecraft.client.resources.model.ModelManager:
		org.violetmoon.quark.mixin.mixins.client.accessor.AccessorModelManager (quark.mixins.json)
		appeng.mixins.unlitquad.ModelManagerMixin (ae2.mixins.json)
		org.embeddedt.modernfix.common.mixin.perf.dynamic_resources.ModelManagerMixin (modernfix-common.mixins.json)
		net.fabricmc.fabric.mixin.resource.loader.client.KeyedResourceReloadListenerClientMixin (fabric-resource-loader-v0.client.mixins.json)
		dev.emi.emi.mixin.accessor.BakedModelManagerAccessor (emi.mixins.json)
		net.fabricmc.fabric.mixin.client.model.loading.BakedModelManagerMixin (fabric-model-loading-api-v1.mixins.json)
		com.bawnorton.allthetrims.mixin.client.BakedModelManagerMixin (allthetrims-common.mixins.json)
		vazkii.botania.mixin.client.ModelManagerAccessor (botania_xplat.mixins.json)
		org.betterx.bclib.mixin.client.ModelManagerMixin (bclib.mixins.client.json)
	net.minecraft.server.packs.resources.SimpleReloadInstance:
		net.fabricmc.fabric.mixin.resource.loader.SimpleResourceReloadMixin (fabric-resource-loader-v0.mixins.json)
		fzzyhmstrs.emi_loot.mixins.SimpleResourceReloadMixin (emi_loot-common.mixins.json)
	net.minecraft.server.packs.resources.ReloadableResourceManager:
		net.fabricmc.fabric.mixin.resource.loader.ReloadableResourceManagerImplMixin (fabric-resource-loader-v0.mixins.json)
		org.embeddedt.modernfix.common.mixin.feature.measure_time.SimpleReloadableResourceManagerMixin (modernfix-common.mixins.json)
		org.embeddedt.modernfix.common.mixin.perf.resourcepacks.ReloadableResourceManagerMixin (modernfix-common.mixins.json)
	net.minecraft.client.Minecraft:
		org.betterx.bclib.mixin.client.MinecraftMixin (bclib.mixins.client.json)
		baguchan.tofucraft.mixin.client.MinecraftMixin (tofucraft.mixins.json)
		net.fabricmc.fabric.mixin.event.lifecycle.client.MinecraftClientMixin (fabric-lifecycle-events-v1.client.mixins.json)
		reborncore.client.mixin.MixinMinecraftClient (reborncore.client.mixins.json)
		net.fabricmc.fabric.mixin.networking.client.accessor.MinecraftClientAccessor (fabric-networking-api-v1.client.mixins.json)
		de.keksuccino.konkrete.mixin.client.MixinMinecraft (konkrete.mixin.json)
		fuzs.resourcepackoverrides.mixin.client.MinecraftMixin (resourcepackoverrides.common.mixins.json)
		traben.entity_model_features.mixin.accessor.MinecraftClientAccessor (entity_model_features-common.mixins.json)
		me.jellysquid.mods.sodium.mixin.core.MinecraftClientMixin (embeddium.mixins.json)
		fuzs.pickupnotifier.mixin.client.MinecraftMixin (pickupnotifier.common.mixins.json)
		xaeroplus.mixin.client.mc.MixinMinecraftClient (xaeroplus.mixins.json)
		com.aizistral.nochatreports.common.mixins.client.MixinMinecraft (mixins/common/nochatreports.mixins.json)
		traben.entity_texture_features.mixin.reloading.MixinMinecraftClient (entity_texture_features-common.mixins.json)
		forge.me.thosea.badoptimizations.mixin.MixinClient (forge-badoptimizations.mixins.json)
		org.betterx.betterend.mixin.client.MinecraftClientMixin (betterend.mixins.client.json)
		codes.ztereohype.nicerskies.mixin.MinecraftMixin (nicer_skies.mixins.json)
		appeng.mixins.PickColorMixin (ae2.mixins.json)
		me.jellysquid.mods.sodium.mixin.core.render.MinecraftAccessor (embeddium.mixins.json)
		traben.entity_model_features.mixin.MixinResourceReload (entity_model_features-common.mixins.json)
		dev.su5ed.sinytra.connectorextras.geckolibcompat.mixin.MinecraftMixin (mixins.connectorextras_geckolib_fabric_compat.json)
		de.keksuccino.drippyloadingscreen.mixin.mixins.client.IMixinMinecraft (drippyloadingscreen.mixin.json)
		net.createmod.ponder.mixin.client.WindowResizeMixin (ponder-common.mixins.json)
		tschipp.carryon.mixin.MinecraftMixin (carryon.mixins.json)
		io.socol.betterthirdperson.mixin.MinecraftMixin (betterthirdperson.mixins.json)
		dev.engine_room.flywheel.impl.mixin.MinecraftMixin (flywheel.impl.mixins.json)
		de.cheaterpaul.fallingleaves.mixin.MinecraftClientMixin (fallingleaves.mixins.json)
		blusunrize.immersiveengineering.mixin.accessors.client.MinecraftAccess (immersiveengineering.mixins.json)
		com.biomemusic.mixin.ClientMusicChoiceMixin (biomemusic.mixins.json)
		io.github.mortuusars.exposure.mixin.MinecraftMixin (exposure-common.mixins.json)
		com.anthonyhilyard.iceberg.mixin.MinecraftMixin (iceberg.mixins.json)
		org.sinytra.connector.mod.mixin.registries.MinecraftMixin (connectormod.mixins.json)
		org.violetmoon.quark.mixin.mixins.client.MinecraftMixin (quark.mixins.json)
		net.bettercombat.mixin.client.MinecraftClientAccessor (bettercombat.mixins.json)
		de.keksuccino.drippyloadingscreen.mixin.mixins.client.MixinMinecraft (drippyloadingscreen.mixin.json)
		net.geforcemods.securitycraft.mixin.camera.MinecraftMixin (securitycraft.mixins.json)
		org.embeddedt.modernfix.common.mixin.bugfix.concurrency.MinecraftMixin (modernfix-common.mixins.json)
		org.sinytra.connector.mod.mixin.boot.MinecraftMixin (connectormod.mixins.json)
		dev.lambdaurora.spruceui.mixin.MinecraftClientMixin (spruceui.mixins.json)
		vazkii.botania.mixin.client.MinecraftAccessor (botania_xplat.mixins.json)
		net.darkhax.bookshelf.mixin.accessors.client.AccessorMinecraft (bookshelf.common.mixins.json)
		de.keksuccino.fancymenu.mixin.client.MixinMinecraft (fancymenu.general.mixin.json)
		net.fabricmc.fabric.mixin.registry.sync.client.MinecraftClientMixin (fabric-registry-sync-v0.client.mixins.json)
		dev.su5ed.sinytra.connectorextras.archbridge.mixin.MinecraftMixin (connectorextras_architectury_bridge.mixins.json)
		org.embeddedt.modernfix.common.mixin.bugfix.world_leaks.MinecraftMixin (modernfix-common.mixins.json)
		com.railwayteam.railways.mixin.conductor_possession.MixinMinecraft (railways-common.mixins.json)
		dev.emi.emi.mixin.MinecraftClientMixin (emi.mixins.json)
		io.wispforest.owo.mixin.ui.MinecraftClientMixin (owo.mixins.json)
		net.bettercombat.mixin.client.MinecraftClientInject (bettercombat.mixins.json)
		com.teampotato.redirectionor.mixin.net.minecraft.client.MinecraftMixin (redirectionor.mixins.json)
		net.fabricmc.fabric.mixin.event.interaction.client.MinecraftClientMixin (fabric-events-interaction-v0.client.mixins.json)
		draylar.omegaconfig.mixin.ClientMixin (omega-config.mixins.json)
		com.hypherionmc.craterlib.mixin.events.client.MinecraftMixin (craterlib.mixins.json)
		com.hollingsworth.arsnouveau.common.mixin.camera.MinecraftMixin (ars_nouveau.mixins.json)
		dev.architectury.mixin.forge.MixinMinecraft (architectury.mixins.json)
		io.redspace.ironsspellbooks.mixin.MinecraftMixin (mixins.irons_spellbooks.json)
		org.embeddedt.modernfix.common.mixin.perf.dedicated_reload_executor.MinecraftMixin (modernfix-common.mixins.json)
		net.blay09.mods.balm.mixin.MinecraftMixin (balm.mixins.json)
		com.telepathicgrunt.the_bumblezone.mixin.client.MinecraftMixin (the_bumblezone-common.mixins.json)
		net.fabricmc.fabric.mixin.screen.MinecraftClientMixin (fabric-screen-api-v1.mixins.json)
		org.embeddedt.modernfix.forge.mixin.feature.measure_time.MinecraftMixin_Forge (modernfix-forge.mixins.json)
		de.siphalor.amecs.impl.mixin.MixinMinecraftClient (amecsapi.mixins.json)
		com.hollingsworth.arsnouveau.common.mixin.light.ClientMixin (ars_nouveau.mixins.json)
		de.keksuccino.fancymenu.mixin.client.IMixinMinecraft (fancymenu.general.mixin.json)
		io.wispforest.owo.mixin.MinecraftClientMixin (owo.mixins.json)
		mod.azure.azurelib.mixins.MinecraftMixin (azurelib.forge.mixins.json)
		com.github.alexmodguy.alexscaves.mixin.client.MinecraftMixin (alexscaves.mixins.json)
		dev.su5ed.sinytra.connectorextras.modmenu.mixin.MinecraftMixin (mixins.connectorextras_modmenu_bridge.json)
		org.embeddedt.modernfix.common.mixin.feature.measure_time.MinecraftMixin (modernfix-common.mixins.json)
		org.embeddedt.modernfix.common.mixin.perf.blast_search_trees.MinecraftMixin (modernfix-common.mixins.json)
-- Initialization --
Details:
	Modules: 
		ADVAPI32.dll:Advanced Windows 32 ベース API:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		COMCTL32.dll:ユーザー エクスペリエンス コントロール ライブラリ:6.10 (WinBuild.160101.0800):Microsoft Corporation
		CRYPT32.dll:Crypto API32:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		CRYPTBASE.dll:Base cryptographic API DLL:10.0.26100.4652 (WinBuild.160101.0800):Microsoft Corporation
		CRYPTSP.dll:Cryptographic Service Provider API:10.0.26100.4652 (WinBuild.160101.0800):Microsoft Corporation
		CoreMessaging.dll:Microsoft CoreMessaging Dll:10.0.26100.4202 (WinBuild.160101.0800):Microsoft Corporation
		DBGHELP.DLL:Windows Image Helper:10.0.26100.4202 (WinBuild.160101.0800):Microsoft Corporation
		DEVOBJ.dll:Device Information Set DLL:10.0.26100.1150 (WinBuild.160101.0800):Microsoft Corporation
		DNSAPI.dll:DNS クライアント API DLL:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		GDI32.dll:GDI Client DLL:10.0.26100.4484 (WinBuild.160101.0800):Microsoft Corporation
		GLU32.dll:OpenGL ユーティリティ ライブラリ DLL:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		IMM32.DLL:Multi-User Windows IMM32 API Client DLL:10.0.26100.4484 (WinBuild.160101.0800):Microsoft Corporation
		IPHLPAPI.DLL:IP ヘルパー API:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		KERNEL32.DLL:Windows NT ベース API クライアント DLL:10.0.26100.4484 (WinBuild.160101.0800):Microsoft Corporation
		KERNELBASE.dll:Windows NT ベース API クライアント DLL:10.0.26100.4484 (WinBuild.160101.0800):Microsoft Corporation
		MMDevApi.dll:MMDevice API:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		MSCTF.dll:MSCTF サーバー DLL:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		MpOav.dll:IOfficeAntiVirus Module:4.18.25060.7 (c882211f69a885f9c0b68229ca4e1040a44b9b85):Microsoft Corporation
		NSI.dll:NSI User-mode interface DLL:10.0.26100.4652 (WinBuild.160101.0800):Microsoft Corporation
		NTASN1.dll:Microsoft ASN.1 API:10.0.26100.1 (WinBuild.160101.0800):Microsoft Corporation
		OLEAUT32.dll:OLEAUT32.DLL:10.0.26100.4484 (WinBuild.160101.0800):Microsoft Corporation
		Oleacc.dll:Active Accessibility Core Component:7.2.26100.4484 (WinBuild.160101.0800):Microsoft Corporation
		OpenAL.dll:Main implementation library:1.21.1:
		POWRPROF.dll:電源プロファイル ヘルパー DLL:10.0.26100.4202 (WinBuild.160101.0800):Microsoft Corporation
		PSAPI.DLL:Process Status Helper:10.0.26100.1 (WinBuild.160101.0800):Microsoft Corporation
		RPCRT4.dll:リモート プロシージャ コール ランタイム:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		SETUPAPI.dll:Windows セットアップ API:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		SHCORE.dll:SHCORE:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		SHELL32.dll:Windows シェル共通 DLL:10.0.26100.4202 (WinBuild.160101.0800):Microsoft Corporation
		UMPDC.dll:User Mode Power Dependency Coordinator:10.0.26100.1301 (WinBuild.160101.0800):Microsoft Corporation
		USER32.dll:マルチユーザー Windows ユーザー API クライアント DLL:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		USERENV.dll:Userenv:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		VCRUNTIME140.dll:Microsoft® C Runtime Library:14.38.33135.0:Microsoft Corporation
		VERSION.dll:Version Checking and File Installation Libraries:10.0.26100.1150 (WinBuild.160101.0800):Microsoft Corporation
		WINHTTP.dll:Windows HTTP サービス:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		WINMM.dll:MCI API DLL:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		WINSTA.dll:Winstation Library:10.0.26100.4484 (WinBuild.160101.0800):Microsoft Corporation
		WINTRUST.dll:Microsoft Trust Verification APIs:10.0.26100.4652 (WinBuild.160101.0800):Microsoft Corporation
		WS2_32.dll:Windows Socket 2.0 32 ビット DLL:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		WTSAPI32.dll:Windows Remote Desktop Session Host Server SDK APIs:10.0.26100.4484 (WinBuild.160101.0800):Microsoft Corporation
		amsi.dll:Anti-Malware Scan Interface:10.0.26100.1150 (WinBuild.160101.0800):Microsoft Corporation
		apphelp.dll:アプリケーションの互換性クライアント ライブラリ:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		awt.dll:OpenJDK Platform binary:17.0.15.0:Microsoft
		bcrypt.dll:Windows 暗号化プリミティブ ライブラリ:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		bcryptPrimitives.dll:Windows Cryptographic Primitives Library:10.0.26100.4652 (WinBuild.160101.0800):Microsoft Corporation
		cfgmgr32.dll:Configuration Manager DLL:10.0.26100.4202 (WinBuild.160101.0800):Microsoft Corporation
		clbcatq.dll:COM+ Configuration Catalog:2001.12.10941.16384 (WinBuild.160101.0800):Microsoft Corporation
		combase.dll:Windows 用 Microsoft COM:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		cryptnet.dll:Crypto Network Related API:10.0.26100.3624 (WinBuild.160101.0800):Microsoft Corporation
		dbgcore.DLL:Windows Core Debugging Helpers:10.0.26100.4484 (WinBuild.160101.0800):Microsoft Corporation
		dhcpcsvc.DLL:DHCP クライアント サービス:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		dhcpcsvc6.DLL:DHCPv6 クライアント:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		dinput8.dll:Microsoft DirectInput:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		drvstore.dll:Driver Store API:10.0.26100.4484 (WinBuild.160101.0800):Microsoft Corporation
		dwmapi.dll:Microsoft デスクトップ ウィンドウ マネージャー API:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		dxcore.dll:DXCore:10.0.26100.4484 (WinBuild.160101.0800):Microsoft Corporation
		extnet.dll:OpenJDK Platform binary:17.0.15.0:Microsoft
		fastprox.dll:WMI Custom Marshaller:10.0.26100.3624 (WinBuild.160101.0800):Microsoft Corporation
		fwpuclnt.dll:FWP/IPsec ユーザー モード API:10.0.26100.3915 (WinBuild.160101.0800):Microsoft Corporation
		gdi32full.dll:GDI Client DLL:10.0.26100.4652 (WinBuild.160101.0800):Microsoft Corporation
		glfw.dll:GLFW 3.4.0 DLL:3.4.0:GLFW
		icm32.dll:Microsoft Color Management Module (CMM):10.0.26100.2314 (WinBuild.160101.0800):Microsoft Corporation
		imagehlp.dll:Windows NT Image Helper:10.0.26100.4202 (WinBuild.160101.0800):Microsoft Corporation
		inputhost.dll:InputHost:10.0.26100.4484 (WinBuild.160101.0800):Microsoft Corporation
		java.dll:OpenJDK Platform binary:17.0.15.0:Microsoft
		javaw.exe:OpenJDK Platform binary:17.0.15.0:Microsoft
		jemalloc.dll
		jimage.dll:OpenJDK Platform binary:17.0.15.0:Microsoft
		jli.dll:OpenJDK Platform binary:17.0.15.0:Microsoft
		jna14398192294757243312.dll:JNA native library:6.1.4:Java(TM) Native Access (JNA)
		jsvml.dll:OpenJDK Platform binary:17.0.15.0:Microsoft
		jvm.dll:OpenJDK 64-Bit server VM:17.0.15.0:Microsoft
		kernel.appcore.dll:AppModel API Host:10.0.26100.4202 (WinBuild.160101.0800):Microsoft Corporation
		lwjgl.dll
		lwjgl_opengl.dll
		lwjgl_stb.dll
		management.dll:OpenJDK Platform binary:17.0.15.0:Microsoft
		management_ext.dll:OpenJDK Platform binary:17.0.15.0:Microsoft
		msasn1.dll:ASN.1 Runtime APIs:10.0.26100.4652 (WinBuild.160101.0800):Microsoft Corporation
		mscms.dll:Microsoft カラー マッチング システム DLL:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		msvcp140.dll:Microsoft® C Runtime Library:14.38.33135.0:Microsoft Corporation
		msvcp_win.dll:Microsoft® C Runtime Library:10.0.26100.4652 (WinBuild.160101.0800):Microsoft Corporation
		msvcrt.dll:Windows NT CRT DLL:7.0.26100.4652 (WinBuild.160101.0800):Microsoft Corporation
		mswsock.dll:Microsoft Windows Sockets 2.0 サービス プロバイダー:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		napinsp.dll:電子メール ネーミング Shim プロバイダー:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		ncrypt.dll:Windows NCrypt ルーター:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		net.dll:OpenJDK Platform binary:17.0.15.0:Microsoft
		nio.dll:OpenJDK Platform binary:17.0.15.0:Microsoft
		nlansp_c.dll:NLA Namespace Service Provider DLL:10.0.26100.4484 (WinBuild.160101.0800):Microsoft Corporation
		ntdll.dll:NT レイヤー DLL:10.0.26100.4484 (WinBuild.160101.0800):Microsoft Corporation
		ntmarta.dll:Windows NT MARTA プロバイダー:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		nvgpucomp64.dll:NVIDIA GPU Compiler Driver, Version 572.16 :32.0.15.7216:NVIDIA Corporation
		nvoglv64.dll:NVIDIA Compatible OpenGL ICD:32.0.15.7216:NVIDIA Corporation
		nvspcap64.dll:NVIDIA Game Proxy:3.28.0.417:NVIDIA Corporation
		ole32.dll:Windows 用 Microsoft OLE:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		opengl32.dll:OpenGL Client DLL:10.0.26100.4484 (WinBuild.160101.0800):Microsoft Corporation
		pdh.dll:Windows パフォーマンス データ ヘルパー DLL:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		perfos.dll:Windows システム パフォーマンス オブジェクト DLL:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		perfproc.dll:Windows システム プロセス パフォーマンス オブジェクト DLL:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		pfclient.dll:SysMain Client:10.0.26100.4202 (WinBuild.160101.0800):Microsoft Corporation
		profapi.dll:User Profile Basic API:10.0.26100.4484 (WinBuild.160101.0800):Microsoft Corporation
		rasadhlp.dll:Remote Access AutoDial Helper:10.0.26100.1150 (WinBuild.160101.0800):Microsoft Corporation
		rsaenh.dll:Microsoft Enhanced Cryptographic Provider:10.0.26100.1 (WinBuild.160101.0800):Microsoft Corporation
		sapi.dll:Speech API:5.3.29825.00 (WinBuild.160101.0800):Microsoft Corporation
		sechost.dll:Host for SCM/SDDL/LSA Lookup APIs:10.0.26100.1 (WinBuild.160101.0800):Microsoft Corporation
		shlwapi.dll:シェル ライトウェイト ユーティリティ ライブラリ:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		sunmscapi.dll:OpenJDK Platform binary:17.0.15.0:Microsoft
		textinputframework.dll:"TextInputFramework.DYNLINK":10.0.26100.4484 (WinBuild.160101.0800):Microsoft Corporation
		ucrtbase.dll:Microsoft® C Runtime Library:10.0.26100.4652 (WinBuild.160101.0800):Microsoft Corporation
		uxtheme.dll:Microsoft UxTheme ライブラリ:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		vcruntime140_1.dll:Microsoft® C Runtime Library:14.38.33135.0:Microsoft Corporation
		verify.dll:OpenJDK Platform binary:17.0.15.0:Microsoft
		wbemcomn.dll:WMI:10.0.26100.1150 (WinBuild.160101.0800):Microsoft Corporation
		wbemprox.dll:WMI:10.0.26100.4202 (WinBuild.160101.0800):Microsoft Corporation
		wbemsvc.dll:WMI:10.0.26100.4202 (WinBuild.160101.0800):Microsoft Corporation
		win32u.dll:Win32u:10.0.26100.4652 (WinBuild.160101.0800):Microsoft Corporation
		windows.staterepositorycore.dll:Windows StateRepository API Core:10.0.26100.4652 (WinBuild.160101.0800):Microsoft Corporation
		windows.storage.dll:Microsoft WinRT ストレージ API:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		winrnr.dll:LDAP RnR Provider DLL:10.0.26100.1882 (WinBuild.160101.0800):Microsoft Corporation
		wintypes.dll:Windows ベース タイプ DLL:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		wldp.dll:Windows のロックダウン ポリシー:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		wshbth.dll:Windows Sockets Helper DLL:10.0.26100.4061 (WinBuild.160101.0800):Microsoft Corporation
		wshunix.dll:AF_UNIX Winsock2 Helper DLL:10.0.26100.1 (WinBuild.160101.0800):Microsoft Corporation
		xinput1_4.dll:Microsoft 共通コントローラー API:10.0.26100.2308 (WinBuild.160101.0800):Microsoft Corporation
		zip.dll:OpenJDK Platform binary:17.0.15.0:Microsoft
Stacktrace:
	at net.minecraft.client.main.Main.main(Main.java:182) ~[minecraft-1.20.1-client.jar:?] {re:mixin,pl:connector_pre_launch:A,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:mixins.emibridge.json:MainEntrypointMixin from mod connectorextras_emi_bridge,pl:mixin:APP:cryonicconfig.mixins.json:client.MainMixin from mod cryonicconfig,pl:mixin:A,pl:connector_pre_launch:A,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:569) ~[?:?] {re:mixin}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:126) ~[loader-47.2.2.jar:47.2] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:114) ~[loader-47.2.2.jar:47.2] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.runService(CommonClientLaunchHandler.java:24) ~[loader-47.2.2.jar:47.2] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.lambda$launchService$4(CommonLaunchHandler.java:108) ~[loader-47.2.2.jar:47.2] {}
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
	at io.github.zekerzhayard.forgewrapper.installer.Main.main(Main.java:69) ~[?:?] {}
	at org.prismlauncher.launcher.impl.StandardLauncher.launch(StandardLauncher.java:105) ~[?:?] {}
	at org.prismlauncher.EntryPoint.listen(EntryPoint.java:129) ~[?:?] {}
	at org.prismlauncher.EntryPoint.main(EntryPoint.java:70) ~[?:?] {}

Mixins in Heaven:
	net.minecraft.client.main.Main:
		com.periut.cryonicconfig.mixin.client.MainMixin (cryonicconfig.mixins.json)
		dev.su5ed.sinytra.connectorextras.emibridge.mixin.MainEntrypointMixin (mixins.emibridge.json)

-- System Details --
Details:
	Minecraft Version: 1.20.1
	Minecraft Version ID: 1.20.1
	Operating System: Windows 11 (amd64) version 10.0
	Java Version: 17.0.15, Microsoft
	Java VM Version: OpenJDK 64-Bit Server VM (mixed mode), Microsoft
	Memory: 1580105408 bytes (1506 MiB) / 4454350848 bytes (4248 MiB) up to 17179869184 bytes (16384 MiB)
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
	Virtual memory max (MB): 52092.21
	Virtual memory used (MB): 33943.50
	Swap memory total (MB): 19456.00
	Swap memory used (MB): 760.69
	JVM Flags: 3 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xms512m -Xmx16384m
	Launched Version: 1.20.1
	Backend library: LWJGL version 3.3.1 build 7
	Backend API: NVIDIA GeForce RTX 3060 Ti/PCIe/SSE2 GL version 4.6.0 NVIDIA 572.16, NVIDIA Corporation
	Window size: <not initialized>
	GL Caps: Using framebuffer using OpenGL 3.2
	GL debug messages: 
	Using VBOs: Yes
	Is Modded: Definitely; Client brand changed to 'forge'
	Type: Client (map_client.txt)
	CPU: 16x Intel(R) Core(TM) i7-10700F CPU @ 2.90GHz
	Sinytra Connector: 1.0.0-beta.46+1.20.1
		SINYTRA CONNECTOR IS PRESENT!
		Please verify issues are not caused by Connector before reporting them to mod authors. If you're unsure, file a report on Connector's issue tracker.
		Connector's issue tracker can be found at https://github.com/Sinytra/Connector/issues.
		Installed Fabric mods:
		| ================================================== | ============================== | ============================== | ==================== |
		| TechReborn-5.8.7_mapped_srg_1.20.1.jar             | Tech Reborn                    | techreborn                     | 5.8.7                |
		| nicer-skies-1.3.0+1.20.1_mapped_srg_1.20.1.jar     | Nicer Skies                    | nicer_skies                    | 1.3.0                |
		| RebornCore-5.8.7$energy-3.0.0_mapped_srg_1.20.1.ja | Energy                         | team_reborn_energy             | 3.0.0                |
		| bettercombat-fabric-1.8.4+1.20.1$mixinextras-fabri | MixinExtras                    | com_github_llamalad7_mixinextr | 0.2.0                |
		| RebornCore-5.8.7_mapped_srg_1.20.1.jar             | Reborn Core                    | reborncore                     | 5.8.7                |
		| Prominent_OST-GLOBAL-MC1.20.1-1.0.0_mapped_srg_1.2 | Prominence Original Soundtrack | prominent_ost                  | 1.0.0                |
		| CIA-1.1.0-Forge-MC1.20.1_mapped_srg_1.20.1.jar     | Custom Item Attributes (CIA)   | customitemattributes           | 1.1.0                |
		| Prominent-GLOBAL-MC1.20.1-1.6.0_mapped_srg_1.20.1. | Prominent                      | prominent                      | 1.4.2                |
		| variety-1.0.0_mapped_srg_1.20.1.jar                | Variety                        | variety                        | 1.0.0                |
		| Prominent_UI-1.0.0_mapped_srg_1.20.1.jar           | Prominent UI Tweaks            | prominent_ui                   | 1.0.0                |
		| Eldritch_End-FORGE-MC1.20.1-0.2.31_mapped_srg_1.20 | Eldritch End                   | eldritch_end                   | 0.2.31               |
		| minecells-1.8.3$gimm1q-0.5.3_mapped_srg_1.20.1.jar | gimm1q                         | gimm1q                         | 0.5.3                |
		| Shield_Overhaul-FABRIC-MC1.20.1-1.0.4_mapped_srg_1 | Shield Overhaul                | shield_overhaul                | 1.0.3                |
		| bettercombat-fabric-1.8.4+1.20.1_mapped_srg_1.20.1 | Better Combat                  | bettercombat                   | 1.8.41.20.1          |
		| owo-lib-0.11.2+1.20$jankson-1.2.2_mapped_srg_1.20. | jankson                        | blue_endless_jankson           | 1.2.2                |
		| better-end-4.0.11_mapped_srg_1.20.1.jar            | Better End                     | betterend                      | 4.0.11               |
		| minecells-1.8.3$omega-config-base-1.2.3-1.18.1_map | OmegaConfig                    | omega_config                   | 1.2.3-1.18.1         |
		| bclib-3.0.14$wunderlib-1.1.5_mapped_srg_1.20.1.jar | WunderLib                      | wunderlib                      | 1.1.5                |
		| bclib-3.0.14_mapped_srg_1.20.1.jar                 | BCLib                          | bclib                          | 3.0.14               |
		| ReBalance-FORGE-1.0.0_mapped_srg_1.20.1.jar        | ReBalance                      | rebalance                      | 1.0.0                |
		| owo-lib-0.11.2+1.20_mapped_srg_1.20.1.jar          | oωo                            | owo                            | 0.11.21.20           |
		| Shield_Overhaul-FABRIC-MC1.20.1-1.0.4$player-anima | Player Animator                | player_animator                | 1.0.2-rc11.20        |
		| minecells-1.8.3_mapped_srg_1.20.1.jar              | Mine Cells                     | minecells                      | 1.8.3                |
		| convenientdecor-0.3.0_mapped_srg_1.20.1.jar        | Convenient Decor               | convenientdecor                | 0.3.0                |
	ModLauncher: 10.0.9+10.0.9+main.dcd20f30
	ModLauncher launch target: forgeclient
	ModLauncher naming: srg
	ModLauncher services: 
		mixin-0.8.5.jar mixin PLUGINSERVICE 
		eventbus-6.0.5.jar eventbus PLUGINSERVICE 
		loader-47.2.2.jar slf4jfixer PLUGINSERVICE 
		loader-47.2.2.jar object_holder_definalize PLUGINSERVICE 
		loader-47.2.2.jar runtime_enum_extender PLUGINSERVICE 
		loader-47.2.2.jar capability_token_subclass PLUGINSERVICE 
		accesstransformers-8.0.4.jar accesstransformer PLUGINSERVICE 
		loader-47.2.2.jar runtimedistcleaner PLUGINSERVICE 
		modlauncher-10.0.9.jar mixin TRANSFORMATIONSERVICE 
		modlauncher-10.0.9.jar fml TRANSFORMATIONSERVICE 
		modlauncher-10.0.9.jar mixin-transmogrifier TRANSFORMATIONSERVICE 
		modlauncher-10.0.9.jar connector_loader TRANSFORMATIONSERVICE 
	FML Language Providers: 
		lowcodefml@47.2
		kotlinforforge@4.8.0
		minecraft@47.2
		javafml@47.2
	Mod List: 
		YungsBetterDungeons-1.20-Forge-4.0.3.jar          |YUNG's Better Dungeons        |betterdungeons                |1.20-Forge-4.0.3    |COMMON_SET|Manifest: NOSIGNATURE
		open-parties-and-claims-forge-1.20.1-0.19.3.jar   |Open Parties and Claims       |openpartiesandclaims          |0.19.3              |COMMON_SET|Manifest: NOSIGNATURE
		kubejs-bridge-1.11.2+1.20.1.jar                   |Connector Extras KubeJS Bridge|connectorextras_kubejs_bridge |1.11.2+1.20.1       |COMMON_SET|Manifest: NOSIGNATURE
		TinkersLevellingAddon-1.20.1-1.4.3.jar            |Tinkers' Levelling Addon      |tinkerslevellingaddon         |1.4.3               |COMMON_SET|Manifest: NOSIGNATURE
		fabric-rendering-fluids-v1-3.0.28+4ac5e37a77.jar  |Fabric Rendering Fluids (v1)  |fabric_rendering_fluids_v1    |3.0.28+4ac5e37a77   |COMMON_SET|Manifest: NOSIGNATURE
		fabric-models-v0-0.4.2+7c3892a477.jar             |Fabric Models (v0)            |fabric_models_v0              |0.4.2+7c3892a477    |COMMON_SET|Manifest: NOSIGNATURE
		ForgeEndertech-1.20.1-11.1.0.0-build.0142.jar     |ForgeEndertech                |forgeendertech                |11.1.0.0            |COMMON_SET|Manifest: NOSIGNATURE
		modernfix-forge-5.15.0+mc1.20.1.jar               |ModernFix                     |modernfix                     |5.15.0+mc1.20.1     |COMMON_SET|Manifest: NOSIGNATURE
		fabric-command-api-v1-1.2.34+f71b366f77.jar       |Fabric Command API (v1)       |fabric_command_api_v1         |1.2.34+f71b366f77   |COMMON_SET|Manifest: NOSIGNATURE
		fabric-block-view-api-v2-1.0.1+0767707077.jar     |Fabric BlockView API (v2)     |fabric_block_view_api_v2      |1.0.1+0767707077    |COMMON_SET|Manifest: NOSIGNATURE
		fabric-command-api-v2-2.2.13+561530ec77.jar       |Fabric Command API (v2)       |fabric_command_api_v2         |2.2.13+561530ec77   |COMMON_SET|Manifest: NOSIGNATURE
		YungsApi-1.20-Forge-4.0.2.jar                     |YUNG's API                    |yungsapi                      |1.20-Forge-4.0.2    |COMMON_SET|Manifest: NOSIGNATURE
		rei-bridge-1.11.2+1.20.1.jar                      |Connector Extras REI Bridge   |connectorextras_rei_bridge    |1.11.2+1.20.1       |COMMON_SET|Manifest: NOSIGNATURE
		clientcrafting-1.20.1-1.7.jar                     |clientcrafting mod            |clientcrafting                |1.20.1-1.7          |COMMON_SET|Manifest: NOSIGNATURE
		Apotheosis-1.20.1-7.2.0.jar                       |Apotheosis                    |apotheosis                    |7.2.0               |COMMON_SET|Manifest: NOSIGNATURE
		clickadv-1.20.1-3.6.jar                           |clickadv mod                  |clickadv                      |1.20.1-3.6          |COMMON_SET|Manifest: NOSIGNATURE
		PickUpNotifier-v8.0.0-1.20.1-Forge.jar            |Pick Up Notifier              |pickupnotifier                |8.0.0               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		SimplyHouses-1.1.4-1.20.1-forge.jar               |Simply Houses                 |simply_houses                 |1.1.4-1.20.1        |COMMON_SET|Manifest: NOSIGNATURE
		create-new-age-forge-1.20.1-1.1.4.jar             |Create: New Age               |create_new_age                |1.1.4               |COMMON_SET|Manifest: NOSIGNATURE
		whatareyouvotingfor2023-1.20.1-1.2.3.jar          |What Are You Voting For? 2023 |whatareyouvotingfor           |1.2.3               |COMMON_SET|Manifest: NOSIGNATURE
		exposure-1.20.1-1.4.1-forge.jar                   |Exposure                      |exposure                      |1.4.1               |COMMON_SET|Manifest: NOSIGNATURE
		YungsBetterNetherFortresses-1.20-Forge-2.0.5.jar  |YUNG's Better Nether Fortresse|betterfortresses              |1.20-Forge-2.0.5    |COMMON_SET|Manifest: NOSIGNATURE
		Paraglider-forge-20.1.1.jar                       |Paraglider                    |paraglider                    |20.1.1              |COMMON_SET|Manifest: NOSIGNATURE
		cloth-config-11.1.118-forge.jar                   |Cloth Config v10 API          |cloth_config                  |11.1.118            |COMMON_SET|Manifest: NOSIGNATURE
		refinedstorage-1.12.4.jar                         |Refined Storage               |refinedstorage                |1.12.4              |COMMON_SET|Manifest: NOSIGNATURE
		embeddium-0.3.31+mc1.20.1.jar                     |Embeddium                     |embeddium                     |0.3.31+mc1.20.1     |COMMON_SET|Manifest: NOSIGNATURE
		TechReborn-5.8.7_mapped_srg_1.20.1.jar            |Tech Reborn                   |techreborn                    |5.8.7               |COMMON_SET|Manifest: NOSIGNATURE
		structure_gel-1.20.1-2.15.1.jar                   |Structure Gel API             |structure_gel                 |2.15.1              |COMMON_SET|Manifest: NOSIGNATURE
		explorations-forge-1.20.1-1.5.2.jar               |Explorations+                 |explorations                  |1.20.1-1.5.2        |COMMON_SET|Manifest: NOSIGNATURE
		corpse-1.20.1-1.0.5.jar                           |Corpse                        |corpse                        |1.20.1-1.0.5        |COMMON_SET|Manifest: NOSIGNATURE
		industrial-foregoing-1.20.1-3.5.9.jar             |Industrial Foregoing          |industrialforegoing           |3.5.9               |COMMON_SET|Manifest: NOSIGNATURE
		handcrafted-forge-1.20.1-3.0.1.jar                |Handcrafted                   |handcrafted                   |3.0.1               |COMMON_SET|Manifest: NOSIGNATURE
		repurposed_structures-7.1.6+1.20.1-forge.jar      |Repurposed Structures         |repurposed_structures         |7.1.6+1.20.1-forge  |COMMON_SET|Manifest: NOSIGNATURE
		BetterCompatibilityChecker-neo-4.0.8+mc1.20.1.jar |Better Compatibility Checker  |bcc                           |4.0.8               |COMMON_SET|Manifest: NOSIGNATURE
		Botania-1.20.1-441-FORGE.jar                      |Botania                       |botania                       |1.20.1-441-FORGE    |COMMON_SET|Manifest: NOSIGNATURE
		Highlighter-1.20.1-forge-1.1.9.jar                |Highlighter                   |highlighter                   |1.1.9               |COMMON_SET|Manifest: NOSIGNATURE
		spark-1.10.53-forge.jar                           |spark                         |spark                         |1.10.53             |COMMON_SET|Manifest: NOSIGNATURE
		Philips-Ruins1.20.1-2.8.jar                       |Philips Ruins                 |philipsruins                  |2.8                 |COMMON_SET|Manifest: NOSIGNATURE
		right-click-harvest-3.2.3+1.20.1-forge.jar        |Right Click Harvest           |rightclickharvest             |3.2.3+1.20.1-forge  |COMMON_SET|Manifest: NOSIGNATURE
		advancednetherite-forge-2.0.2-1.20.1.jar          |Advanced Netherite            |advancednetherite             |2.0.2               |COMMON_SET|Manifest: NOSIGNATURE
		YungsExtras-1.20-Forge-4.0.3.jar                  |YUNG's Extras                 |yungsextras                   |1.20-Forge-4.0.3    |COMMON_SET|Manifest: NOSIGNATURE
		dungeons-and-taverns-3.0.3 [Forge].jar            |Dungeons and Taverns          |mr_dungeons_andtaverns        |3.0.3               |COMMON_SET|Manifest: NOSIGNATURE
		ApothicAttributes-1.20.1-1.2.1.jar                |Apothic Attributes            |attributeslib                 |1.2.1               |COMMON_SET|Manifest: NOSIGNATURE
		bettervillage-forge-1.20.1-3.2.0.jar              |Better village                |bettervillage                 |3.1.0               |COMMON_SET|Manifest: NOSIGNATURE
		cumulus_menus-1.20.1-1.0.0-neoforge.jar           |Cumulus                       |cumulus_menus                 |1.20.1-1.0.0-neoforg|COMMON_SET|Manifest: NOSIGNATURE
		NetherChested-v8.0.1-1.20.1-Forge.jar             |Nether Chested                |netherchested                 |8.0.1               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		emiffect-forge-1.1.2+mc1.20.1.jar                 |EMIffect                      |emiffect                      |1.1.2+mc1.20.1      |COMMON_SET|Manifest: NOSIGNATURE
		flib-1.20.1-0.0.11.jar                            |flib                          |flib                          |0.0.11              |COMMON_SET|Manifest: 1f:47:ac:b1:61:82:96:b8:47:19:16:d2:61:81:11:60:3a:06:4b:61:31:56:7d:44:31:1e:0c:6f:22:5b:4c:ed
		YungsBetterEndIsland-1.20-Forge-2.0.4.jar         |YUNG's Better End Island      |betterendisland               |1.20-Forge-2.0.4    |COMMON_SET|Manifest: NOSIGNATURE
		fabric-rendering-data-attachment-v1-0.3.37+a6081af|Fabric Rendering Data Attachme|fabric_rendering_data_attachme|0.3.37+a6081afc77   |COMMON_SET|Manifest: NOSIGNATURE
		nitrogen_internals-1.20.1-1.0.1-neoforge.jar      |Nitrogen                      |nitrogen_internals            |1.20.1-1.0.1-neoforg|COMMON_SET|Manifest: NOSIGNATURE
		the_bumblezone-7.2.7+1.20.1-forge.jar             |The Bumblezone                |the_bumblezone                |7.2.7+1.20.1-forge  |COMMON_SET|Manifest: NOSIGNATURE
		l2library-2.4.16-slim.jar                         |L2 Library                    |l2library                     |2.4.16              |COMMON_SET|Manifest: NOSIGNATURE
		BetterModsButton-v8.0.2-1.20.1-Forge.jar          |Better Mods Button            |bettermodsbutton              |8.0.2               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		YungsBetterJungleTemples-1.20-Forge-2.0.3.jar     |YUNG's Better Jungle Temples  |betterjungletemples           |1.20-Forge-2.0.3    |COMMON_SET|Manifest: NOSIGNATURE
		Byzantine-1.20.1-11.1.jar                         |Byzantine                     |byzantine                     |11h                 |COMMON_SET|Manifest: NOSIGNATURE
		fabric-client-tags-api-v1-1.1.2+5d6761b877.jar    |Fabric Client Tags            |fabric_client_tags_api_v1     |1.1.2+5d6761b877    |COMMON_SET|Manifest: NOSIGNATURE
		SmartBrainLib-neoforge-1.20.1-1.13.jar            |SmartBrainLib                 |smartbrainlib                 |1.13                |COMMON_SET|Manifest: NOSIGNATURE
		radium-mc1.20.1-0.12.2+git.5f80f74.jar            |Radium                        |radium                        |0.12.2+git.5f80f74  |COMMON_SET|Manifest: NOSIGNATURE
		Kiwi-1.20.1-forge-11.1.1.jar                      |Kiwi Library                  |kiwi                          |11.1.1              |COMMON_SET|Manifest: NOSIGNATURE
		MutantMonsters-v8.0.4-1.20.1-Forge.jar            |Mutant Monsters               |mutantmonsters                |8.0.4               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		VisualWorkbench-v8.0.0-1.20.1-Forge.jar           |Visual Workbench              |visualworkbench               |8.0.0               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		AttributeFix-Forge-1.20.1-21.0.4.jar              |AttributeFix                  |attributefix                  |21.0.4              |COMMON_SET|Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		fabric-screen-handler-api-v1-1.3.30+561530ec77.jar|Fabric Screen Handler API (v1)|fabric_screen_handler_api_v1  |1.3.30+561530ec77   |COMMON_SET|Manifest: NOSIGNATURE
		libraryferret-forge-1.20.1-4.0.0.jar              |Library ferret                |libraryferret                 |4.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		epicsamurai-0.0.26.2-1.20.1-forge.jar             |Epic Samurai                  |epicsamurai                   |0.0.26.2-1.20.1-forg|COMMON_SET|Manifest: NOSIGNATURE
		caelus-forge-3.1.0+1.20.jar                       |Caelus API                    |caelus                        |3.1.0+1.20          |COMMON_SET|Manifest: NOSIGNATURE
		fastasyncworldsave-1.20.1-1.4.jar                 |fastasyncworldsave mod        |fastasyncworldsave            |1.20.1-1.4          |COMMON_SET|Manifest: NOSIGNATURE
		EpheroLib-1.20.1-FORGE-1.2.0.jar                  |BOZOID                        |epherolib                     |0.1.2               |COMMON_SET|Manifest: NOSIGNATURE
		badpackets-forge-0.4.3.jar                        |Bad Packets                   |badpackets                    |0.4.3               |COMMON_SET|Manifest: NOSIGNATURE
		CraterLib-Forge-1.20-2.0.1.jar                    |CraterLib                     |craterlib                     |2.0.1               |COMMON_SET|Manifest: NOSIGNATURE
		snowundertrees-1.20-1.4.1.jar                     |Snow Under Trees              |snowundertrees                |1.4.1               |COMMON_SET|Manifest: NOSIGNATURE
		rare-ice-0.6.0.jar                                |Rare Ice                      |rare_ice                      |0.0NONE             |COMMON_SET|Manifest: NOSIGNATURE
		AnimaticaReforged-1.20.1-0.0.2.jar                |AnimaticaReforged             |animatica                     |1.20.1-0.0.1        |COMMON_SET|Manifest: NOSIGNATURE
		scholar-1.20.1-1.0.0-forge.jar                    |Scholar                       |scholar                       |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		nicer-skies-1.3.0+1.20.1_mapped_srg_1.20.1.jar    |Nicer Skies                   |nicer_skies                   |1.3.0               |COMMON_SET|Manifest: NOSIGNATURE
		fabric-particles-v1-1.1.2+78e1ecb877.jar          |Fabric Particles (v1)         |fabric_particles_v1           |1.1.2+78e1ecb877    |COMMON_SET|Manifest: NOSIGNATURE
		DungeonsArise-1.20.x-2.1.58-release.jar           |When Dungeons Arise           |dungeons_arise                |2.1.58-1.20.x       |COMMON_SET|Manifest: NOSIGNATURE
		hearths-v1.0.0-mc1.20u1.20.1.jar                  |Hearths                       |hearths                       |1.0.0-mc1.20u1.20.1 |COMMON_SET|Manifest: NOSIGNATURE
		smoothchunk-1.20.1-3.5.jar                        |Smoothchunk mod               |smoothchunk                   |1.20.1-3.5          |COMMON_SET|Manifest: NOSIGNATURE
		TerraBlender-forge-1.20.1-3.0.0.169.jar           |TerraBlender                  |terrablender                  |3.0.0.169           |COMMON_SET|Manifest: NOSIGNATURE
		BiomesOPlenty-1.20.1-18.0.0.598.jar               |Biomes O' Plenty              |biomesoplenty                 |18.0.0.598          |COMMON_SET|Manifest: NOSIGNATURE
		ForgeConfigScreens-v8.0.2-1.20.1-Forge.jar        |Forge Config Screens          |forgeconfigscreens            |8.0.2               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		Necronomicon-Forge-1.4.2.jar                      |Necronomicon                  |necronomicon                  |1.4.2               |COMMON_SET|Manifest: NOSIGNATURE
		justenoughbreeding-forge-1.20.x-1.0.12.jar        |Just Enough Breeding          |justenoughbreeding            |1.0.12              |COMMON_SET|Manifest: NOSIGNATURE
		Luna-FORGE-MC1.19.X-1.0.1.jar                     |Luna                          |luna                          |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		fabric-block-api-v1-1.0.11+0e6cb7f777.jar         |Fabric Block API (v1)         |fabric_block_api_v1           |1.0.11+0e6cb7f777   |COMMON_SET|Manifest: NOSIGNATURE
		fabric-resource-conditions-api-v1-2.3.8+9ad825cd77|Fabric Resource Conditions API|fabric_resource_conditions_api|2.3.8+9ad825cd77    |COMMON_SET|Manifest: NOSIGNATURE
		forgeconfigapiport-1.11.2+1.20.1.jar              |Forge Config API Port (Connect|forgeconfigapiport            |8.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		domum_ornamentum-1.20.1-1.0.184-BETA-universal.jar|Domum Ornamentum              |domum_ornamentum              |1.20.1-1.0.184-BETA |COMMON_SET|Manifest: NOSIGNATURE
		betterfpsdist-1.20.1-4.1.jar                      |betterfpsdist mod             |betterfpsdist                 |1.20.1-4.1          |COMMON_SET|Manifest: NOSIGNATURE
		notenoughanimations-forge-1.6.4-mc1.20.jar        |NotEnoughAnimations Mod       |notenoughanimations           |1.6.4               |COMMON_SET|Manifest: NOSIGNATURE
		flywheel-forge-1.20.1-1.0.4.jar                   |Flywheel                      |flywheel                      |1.0.4               |COMMON_SET|Manifest: NOSIGNATURE
		experienceobelisk-v1.4.10-1.20.1.jar              |Experience Obelisk            |experienceobelisk             |1.4.10-1.20.1       |COMMON_SET|Manifest: NOSIGNATURE
		JustEnoughProfessions-forge-1.20.1-3.0.1.jar      |Just Enough Professions (JEP) |justenoughprofessions         |3.0.1               |COMMON_SET|Manifest: NOSIGNATURE
		[1.20.1] SecurityCraft v1.9.8.jar                 |SecurityCraft                 |securitycraft                 |1.9.8               |COMMON_SET|Manifest: NOSIGNATURE
		almostunified-forge-1.20.1-0.9.3.jar              |AlmostUnified                 |almostunified                 |1.20.1-0.9.3        |COMMON_SET|Manifest: NOSIGNATURE
		emi-1.1.2+1.20.1+forge.jar                        |EMI                           |emi                           |1.1.2+1.20.1+forge  |COMMON_SET|Manifest: NOSIGNATURE
		structurize-1.20.1-1.0.718-BETA.jar               |Structurize                   |structurize                   |1.20.1-1.0.718-BETA |COMMON_SET|Manifest: NOSIGNATURE
		AmbientEnvironment-forge-1.20.1-11.0.0.1.jar      |Ambient Environment           |ambientenvironment            |11.0.0.1            |COMMON_SET|Manifest: NOSIGNATURE
		fabric-registry-sync-v0-2.3.3+1c0ea72177.jar      |Fabric Registry Sync (v0)     |fabric_registry_sync_v0       |2.3.3+1c0ea72177    |COMMON_SET|Manifest: NOSIGNATURE
		FastFurnace-1.20.1-8.0.1.jar                      |FastFurnace                   |fastfurnace                   |8.0.1               |COMMON_SET|Manifest: NOSIGNATURE
		embersrekindled-1.20.1-1.2.3.jar                  |Embers Rekindled              |embers                        |1.20.1-1.2.3        |COMMON_SET|Manifest: NOSIGNATURE
		lootr-1.20-0.7.30.73.jar                          |Lootr                         |lootr                         |0.7.29.68           |COMMON_SET|Manifest: NOSIGNATURE
		fabric-object-builder-api-v1-11.1.3+2174fc8477.jar|Fabric Object Builder API (v1)|fabric_object_builder_api_v1  |11.1.3+2174fc8477   |COMMON_SET|Manifest: NOSIGNATURE
		occultism-1.20.1-1.94.1.jar                       |Occultism                     |occultism                     |1.94.1              |COMMON_SET|Manifest: NOSIGNATURE
		christmascolonies-1.2.jar                         |christmascolonies mod         |christmascolonies             |1.2                 |COMMON_SET|Manifest: NOSIGNATURE
		fabric-message-api-v1-5.1.9+52cc178c77.jar        |Fabric Message API (v1)       |fabric_message_api_v1         |5.1.9+52cc178c77    |COMMON_SET|Manifest: NOSIGNATURE
		cosmeticarmorreworked-1.20.1-v1a.jar              |CosmeticArmorReworked         |cosmeticarmorreworked         |1.20.1-v1a          |COMMON_SET|Manifest: 5e:ed:25:99:e4:44:14:c0:dd:89:c1:a9:4c:10:b5:0d:e4:b1:52:50:45:82:13:d8:d0:32:89:67:56:57:01:53
		RebornCore-5.8.7$energy-3.0.0_mapped_srg_1.20.1.ja|Energy                        |team_reborn_energy            |3.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		ad_astra-forge-1.20.1-1.15.5.jar                  |Ad Astra                      |ad_astra                      |1.15.5              |COMMON_SET|Manifest: NOSIGNATURE
		SkyVillages-1.0.2-1.20.1-forge-release.jar        |Sky Villages                  |skyvillages                   |1.0.2-1.20.1-forge  |COMMON_SET|Manifest: NOSIGNATURE
		fabric-renderer-api-v1-3.2.1+1d29b44577.jar       |Fabric Renderer API (v1)      |fabric_renderer_api_v1        |3.2.1+1d29b44577    |COMMON_SET|Manifest: NOSIGNATURE
		alchemylib-1.20.1-1.0.29.jar                      |AlchemyLib                    |alchemylib                    |1.0.29              |COMMON_SET|Manifest: NOSIGNATURE
		fabric-item-api-v1-2.1.28+4d0bbcfa77.jar          |Fabric Item API (v1)          |fabric_item_api_v1            |2.1.28+4d0bbcfa77   |COMMON_SET|Manifest: NOSIGNATURE
		bettercombat-fabric-1.8.4+1.20.1$mixinextras-fabri|MixinExtras                   |com_github_llamalad7_mixinextr|0.2.0               |COMMON_SET|Manifest: NOSIGNATURE
		towntalk-1.20.1-1.0.1.jar                         |TownTalk                      |towntalk                      |1.0.1               |COMMON_SET|Manifest: NOSIGNATURE
		IllagerInvasion-v8.0.3-1.20.1-Forge.jar           |Illager Invasion              |illagerinvasion               |8.0.3               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		Galosphere-1.20.1-1.3.2-Forge.jar                 |Galosphere                    |galosphere                    |1.20.1-1.3.2        |COMMON_SET|Manifest: NOSIGNATURE
		YungsBetterOceanMonuments-1.20-Forge-3.0.3.jar    |YUNG's Better Ocean Monuments |betteroceanmonuments          |1.20-Forge-3.0.3    |COMMON_SET|Manifest: NOSIGNATURE
		dimensionalsycnfixes-1.20.1-0.0.1.jar             |DimensionalSycnFixes          |dimensionalsycnfixes          |1.20.1-0.0.1        |COMMON_SET|Manifest: NOSIGNATURE
		sophisticatedcore-1.20.1-1.2.71.1022.jar          |Sophisticated Core            |sophisticatedcore             |1.2.71.1022         |COMMON_SET|Manifest: NOSIGNATURE
		gpumemleakfix-1.20.1-1.8.jar                      |Gpu memory leak fix           |gpumemleakfix                 |1.20.1-1.8          |COMMON_SET|Manifest: NOSIGNATURE
		structureessentials-1.20.1-3.2.jar                |Structure Essentials mod      |structureessentials           |1.20.1-3.2          |COMMON_SET|Manifest: NOSIGNATURE
		RebornCore-5.8.7_mapped_srg_1.20.1.jar            |Reborn Core                   |reborncore                    |5.8.7               |COMMON_SET|Manifest: NOSIGNATURE
		Prism-1.20.1-forge-1.0.5.jar                      |Prism                         |prism                         |1.0.5               |COMMON_SET|Manifest: NOSIGNATURE
		Placebo-1.20.1-8.6.0.jar                          |Placebo                       |placebo                       |8.6.0               |COMMON_SET|Manifest: NOSIGNATURE
		emi_loot-0.6.5+1.20.1+forge.jar                   |EMI Loot                      |emi_loot                      |0.6.5+1.20.1+forge  |COMMON_SET|Manifest: NOSIGNATURE
		lootintegrations-1.20.1-3.4.jar                   |Lootintegrations mod          |lootintegrations              |1.20.1-3.4          |COMMON_SET|Manifest: NOSIGNATURE
		Item-Obliterator-NeoForge-MC1.20.1-2.3.1.jar      |Item Obliterator              |item_obliterator              |2.3.0               |COMMON_SET|Manifest: NOSIGNATURE
		Bookshelf-Forge-1.20.1-20.1.9.jar                 |Bookshelf                     |bookshelf                     |20.1.9              |COMMON_SET|Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		sophisticatedbackpacks-1.20.1-3.23.19.1263.jar    |Sophisticated Backpacks       |sophisticatedbackpacks        |3.23.19.1263        |COMMON_SET|Manifest: NOSIGNATURE
		bygonenether-1.3.2-1.20.x.jar                     |Bygone Nether                 |bygonenether                  |1.3.2               |COMMON_SET|Manifest: NOSIGNATURE
		carryon-forge-1.20.1-2.1.2.7.jar                  |Carry On                      |carryon                       |2.1.2.7             |COMMON_SET|Manifest: NOSIGNATURE
		ShieldExpansion-1.20.1-1.1.7.jar                  |Shield Expansion              |shieldexp                     |1.1.7               |COMMON_SET|Manifest: NOSIGNATURE
		interiors-0.5.6+forge-mc1.20.1-local.jar          |Create: Interiors             |interiors                     |0.5.6               |COMMON_SET|Manifest: NOSIGNATURE
		dragonfight-1.20.1-4.1.jar                        |dragonfight mod               |dragonfight                   |1.20.1-4.1          |COMMON_SET|Manifest: NOSIGNATURE
		fabric-api-0.92.2+1.11.8+1.20.1.jar               |Forgified Fabric API          |fabric_api                    |0.92.2+1.11.8+1.20.1|COMMON_SET|Manifest: NOSIGNATURE
		modmenu-bridge-1.11.2+1.20.1.jar                  |Connector Extras ModMenu Bridg|connectorextras_modmenu_bridge|1.11.2+1.20.1       |COMMON_SET|Manifest: NOSIGNATURE
		konkrete_forge_1.6.1-2_MC_1.20.jar                |Konkrete                      |konkrete                      |1.6.1               |COMMON_SET|Manifest: NOSIGNATURE
		snowmancy-1.20-1.1.jar                            |Snowmancy                     |snowmancy                     |1.1                 |COMMON_SET|Manifest: NOSIGNATURE
		chipped-forge-1.20.1-3.0.7.jar                    |Chipped                       |chipped                       |3.0.7               |COMMON_SET|Manifest: NOSIGNATURE
		friendsandfoes-flowerymooblooms-forge-mc1.20.1-2.0|Friends&Foes - Flowery Moobloo|flowerymooblooms              |2.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		entity_model_features_forge_1.20.1-1.2.3.jar      |Entity Model Features         |entity_model_features         |1.2.3               |COMMON_SET|Manifest: NOSIGNATURE
		entity_texture_features_forge_1.20.1-5.2.1.jar    |Entity Texture Features       |entity_texture_features       |5.2.1               |COMMON_SET|Manifest: NOSIGNATURE
		AmbientSounds_FORGE_v6.0.1_mc1.20.1.jar           |AmbientSounds                 |ambientsounds                 |6.0.1               |COMMON_SET|Manifest: NOSIGNATURE
		fabric-api-lookup-api-v1-1.6.36+67f9824077.jar    |Fabric API Lookup API (v1)    |fabric_api_lookup_api_v1      |1.6.36+67f9824077   |COMMON_SET|Manifest: NOSIGNATURE
		Boat-Item-View-Forge-1.20.1-0.0.5.jar             |Boat Item View                |boatiview                     |0.0.5               |COMMON_SET|Manifest: NOSIGNATURE
		architectury-bridge-1.11.2+1.20.1.jar             |Connector Extras Architectury |connectorextras_architectury_b|1.11.2+1.20.1       |COMMON_SET|Manifest: NOSIGNATURE
		memorysettings-1.20.1-5.4.jar                     |memorysettings mod            |memorysettings                |1.20.1-5.4          |COMMON_SET|Manifest: NOSIGNATURE
		blockui-1.20.1-1.0.151-BETA.jar                   |UI Library Mod                |blockui                       |1.20.1-1.0.151-BETA |COMMON_SET|Manifest: NOSIGNATURE
		ironchests-5.0.2-forge.jar                        |Iron Chests: Restocked        |ironchests                    |5.0.2               |COMMON_SET|Manifest: NOSIGNATURE
		CerbonsAPI-Forge-1.20.1-1.1.0.jar                 |Cerbons API                   |cerbons_api                   |1.1.0               |COMMON_SET|Manifest: NOSIGNATURE
		Prominent_OST-GLOBAL-MC1.20.1-1.0.0_mapped_srg_1.2|Prominence Original Soundtrack|prominent_ost                 |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		oreexcavation-1.13.174.jar                        |OreExcavation                 |oreexcavation                 |1.13.174            |COMMON_SET|Manifest: NOSIGNATURE
		elevatorid-1.20.1-1.9.1.jar                       |Elevator Mod                  |elevatorid                    |1.20.1-1.9          |COMMON_SET|Manifest: NOSIGNATURE
		Connector-1.0.0-beta.46+1.20.1-mod.jar            |Connector                     |connectormod                  |1.0.0-beta.46+1.20.1|COMMON_SET|Manifest: NOSIGNATURE
		starterkit-1.20.1-5.2.jar                         |Starter Kit                   |starterkit                    |5.2                 |COMMON_SET|Manifest: NOSIGNATURE
		twilightdelight-2.0.4.jar                         |Twilight's Flavor & Delight   |twilightdelight               |2.0.4               |COMMON_SET|Manifest: NOSIGNATURE
		ServerBrowser-1.20-FORGE-1.1.1.jar                |ServerBrowser                 |serverbrowser                 |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		cupboard-1.20.1-2.1.jar                           |Cupboard utilities            |cupboard                      |1.20.1-2.1          |COMMON_SET|Manifest: NOSIGNATURE
		cherishedworlds-forge-6.1.4+1.20.1.jar            |Cherished Worlds              |cherishedworlds               |6.1.4+1.20.1        |COMMON_SET|Manifest: NOSIGNATURE
		The_Undergarden-1.20.1-0.8.9.jar                  |The Undergarden               |undergarden                   |0.8.9               |COMMON_SET|Manifest: NOSIGNATURE
		framework-forge-1.20.1-0.6.16.jar                 |Framework                     |framework                     |0.6.16              |COMMON_SET|Manifest: 0d:78:5f:44:c0:47:0c:8c:e2:63:a3:04:43:d4:12:7d:b0:7c:35:37:dc:40:b1:c1:98:ec:51:eb:3b:3c:45:99
		TofuCraftReload-1.20.1-5.16.1.1.jar               |TofuCraftReload               |tofucraft                     |1.20.1-5.16.1.1     |COMMON_SET|Manifest: NOSIGNATURE
		fabric-key-binding-api-v1-1.0.37+561530ec77.jar   |Fabric Key Binding API (v1)   |fabric_key_binding_api_v1     |1.0.37+561530ec77   |COMMON_SET|Manifest: NOSIGNATURE
		BetterAdvancements-1.20.1-0.3.2.161.jar           |Better Advancements           |betteradvancements            |0.3.2.161           |COMMON_SET|Manifest: NOSIGNATURE
		fabric-transfer-api-v1-3.3.5+631c9cd677.jar       |Fabric Transfer API (v1)      |fabric_transfer_api_v1        |3.3.5+631c9cd677    |COMMON_SET|Manifest: NOSIGNATURE
		EasyMagic-v8.0.1-1.20.1-Forge.jar                 |Easy Magic                    |easymagic                     |8.0.1               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		pehkui-bridge-1.11.2+1.20.1.jar                   |Connector Extras Pehkui Bridge|connectorextras_pehkui_bridge |1.11.2+1.20.1       |COMMON_SET|Manifest: NOSIGNATURE
		fabric-resource-loader-v0-0.11.10+bcd08ed377.jar  |Fabric Resource Loader (v0)   |fabric_resource_loader_v0     |0.11.10+bcd08ed377  |COMMON_SET|Manifest: NOSIGNATURE
		obscure_api-15.jar                                |Obscure API                   |obscure_api                   |15                  |COMMON_SET|Manifest: NOSIGNATURE
		Clumps-forge-1.20.1-12.0.0.3.jar                  |Clumps                        |clumps                        |12.0.0.3            |COMMON_SET|Manifest: NOSIGNATURE
		artifacts-forge-9.2.0.jar                         |Artifacts                     |artifacts                     |9.2.0               |COMMON_SET|Manifest: NOSIGNATURE
		SimpleStorageNetwork-1.20.1-1.10.0.jar            |Simple Storage Network        |storagenetwork                |1.10.0              |COMMON_SET|Manifest: 1f:47:ac:b1:61:82:96:b8:47:19:16:d2:61:81:11:60:3a:06:4b:61:31:56:7d:44:31:1e:0c:6f:22:5b:4c:ed
		decorative_blocks-forge-1.20.1-4.1.3.jar          |Decorative Blocks             |decorative_blocks             |4.1.3               |COMMON_SET|Manifest: NOSIGNATURE
		ExplorersCompass-1.20.1-1.3.3-forge.jar           |Explorer's Compass            |explorerscompass              |1.20.1-1.3.3-forge  |COMMON_SET|Manifest: NOSIGNATURE
		BOMD-Forge-1.20.1-1.1.2.jar                       |Bosses of Mass Destruction    |bosses_of_mass_destruction    |1.1.2               |COMMON_SET|Manifest: NOSIGNATURE
		azurelib-neo-1.20.1-2.0.16.jar                    |AzureLib                      |azurelib                      |2.0.16              |COMMON_SET|Manifest: NOSIGNATURE
		energy-bridge-1.11.2+1.20.1.jar                   |Connector Extras Energy Bridge|connectorextras_energy_bridge |1.11.2+1.20.1       |COMMON_SET|Manifest: NOSIGNATURE
		watut-forge-1.20.1-1.0.13.jar                     |What Are They Up To           |watut                         |1.20.1-1.0.13       |COMMON_SET|Manifest: NOSIGNATURE
		3dskinlayers-forge-1.5.4-mc1.20.1.jar             |3dSkinLayers                  |skinlayers3d                  |1.5.4               |COMMON_SET|Manifest: NOSIGNATURE
		Raided-1.20.1-0.1.3.jar                           |Raided                        |raided                        |0.1.3               |COMMON_SET|Manifest: NOSIGNATURE
		friendsandfoes-forge-mc1.20.1-2.0.4.jar           |Friends&Foes                  |friendsandfoes                |2.0.4               |COMMON_SET|Manifest: NOSIGNATURE
		TConstruct-1.20.1-3.10.1.76.jar                   |Tinkers' Construct            |tconstruct                    |3.10.1.76           |COMMON_SET|Manifest: NOSIGNATURE
		okzoomer-forge-1.20-3.0.1.jar                     |OkZoomer                      |okzoomer                      |3.0.1               |COMMON_SET|Manifest: NOSIGNATURE
		CIA-1.1.0-Forge-MC1.20.1_mapped_srg_1.20.1.jar    |Custom Item Attributes (CIA)  |customitemattributes          |1.1.0               |COMMON_SET|Manifest: NOSIGNATURE
		JustEnoughBeacons-Forge-1.19+-1.1.1.jar           |JustEnoughBeacons             |just_enough_beacons           |1.1.1               |COMMON_SET|Manifest: NOSIGNATURE
		mysterious_mountain_lib-1.5.22-1.20.1.jar         |Mysterious Mountain Lib       |mysterious_mountain_lib       |1.5.22-1.20.1       |COMMON_SET|Manifest: NOSIGNATURE
		fabric-blockrenderlayer-v1-1.1.41+1d0da21e77.jar  |Fabric BlockRenderLayer Regist|fabric_blockrenderlayer_v1    |1.1.41+1d0da21e77   |COMMON_SET|Manifest: NOSIGNATURE
		amecsapi-1.5.3+mc1.20-pre1.jar                    |Amecs API                     |amecsapi                      |1.5.3+mc1.20-pre1   |COMMON_SET|Manifest: NOSIGNATURE
		CreativeCore_FORGE_v2.11.28_mc1.20.1.jar          |CreativeCore                  |creativecore                  |2.11.28             |COMMON_SET|Manifest: NOSIGNATURE
		LegendaryTooltips-1.20.1-forge-1.4.5.jar          |Legendary Tooltips            |legendarytooltips             |1.4.5               |COMMON_SET|Manifest: NOSIGNATURE
		mes-1.3-1.20-forge.jar                            |Moog's End Structures         |mes                           |1.3-1.20-forge      |COMMON_SET|Manifest: NOSIGNATURE
		FastWorkbench-1.20.1-8.0.2.jar                    |Fast Workbench                |fastbench                     |8.0.2               |COMMON_SET|Manifest: NOSIGNATURE
		NoSeeNoTick-2.0.0-1.20.1.jar                      |No See, No tick               |noseenotick                   |2.0.0-build.9999    |COMMON_SET|Manifest: NOSIGNATURE
		betterarcheology-1.1.0.jar                        |Better Archeology             |betterarcheology              |1.1.0               |COMMON_SET|Manifest: NOSIGNATURE
		fabric-biome-api-v1-13.0.13+dc36698e77.jar        |Fabric Biome API (v1)         |fabric_biome_api_v1           |13.0.13+dc36698e77  |COMMON_SET|Manifest: NOSIGNATURE
		buildinggadgets2-1.0.7.jar                        |Building Gadgets 2            |buildinggadgets2              |1.0.7               |COMMON_SET|Manifest: NOSIGNATURE
		fancymenu_forge_2.14.9-3_MC_1.20.1.jar            |FancyMenu                     |fancymenu                     |2.14.9              |COMMON_SET|Manifest: NOSIGNATURE
		minecolonies-1.20.1-1.1.530-BETA.jar              |MineColonies                  |minecolonies                  |1.20.1-1.1.530-BETA |COMMON_SET|Manifest: NOSIGNATURE
		ferritecore-6.0.1-forge.jar                       |Ferrite Core                  |ferritecore                   |6.0.1               |COMMON_SET|Manifest: 41:ce:50:66:d1:a0:05:ce:a1:0e:02:85:9b:46:64:e0:bf:2e:cf:60:30:9a:fe:0c:27:e0:63:66:9a:84:ce:8a
		charmofundying-forge-6.4.2+1.20.1.jar             |Charm of Undying              |charmofundying                |6.4.2+1.20.1        |COMMON_SET|Manifest: NOSIGNATURE
		Plenty_of_Golems-V1.3.1-Forge_1.20.1.jar          |plenty of golems              |plenty_of_golems              |1.3.0               |COMMON_SET|Manifest: NOSIGNATURE
		BadOptimizations-1.6.3.jar                        |BadOptimizations              |badoptimizations              |1.6.3               |COMMON_SET|Manifest: NOSIGNATURE
		create_enchantment_industry-1.3.2-for-create-6.0.4|Create Enchantment Industry   |create_enchantment_industry   |1.3.2-for-create-6.0|COMMON_SET|Manifest: NOSIGNATURE
		OverflowingBars-v8.0.0-1.20.1-Forge.jar           |Overflowing Bars              |overflowingbars               |8.0.0               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		OpenLoader-Forge-1.20.1-19.0.3.jar                |OpenLoader                    |openloader                    |19.0.3              |COMMON_SET|Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		createaddition-1.20.1-1.3.1.jar                   |Create Crafts & Additions     |createaddition                |1.20.1-1.3.1        |COMMON_SET|Manifest: NOSIGNATURE
		auudio_forge_1.0.3_MC_1.19.3.jar                  |Auudio                        |auudio                        |1.0.3               |COMMON_SET|Manifest: NOSIGNATURE
		EasyAnvils-v8.0.1-1.20.1-Forge.jar                |Easy Anvils                   |easyanvils                    |8.0.1               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		riverredux-0.3.1.jar                              |RiverRedux                    |riverredux                    |0.3.1               |COMMON_SET|Manifest: NOSIGNATURE
		player-animation-lib-forge-1.0.2-rc1+1.20.jar     |Player Animator               |playeranimator                |1.0.2-rc1+1.20      |COMMON_SET|Manifest: NOSIGNATURE
		irons_spellbooks-1.20.1-3.4.0.9.jar               |Iron's Spells 'n Spellbooks   |irons_spellbooks              |1.20.1-3.4.0.9      |COMMON_SET|Manifest: NOSIGNATURE
		botarium-forge-1.20.1-2.3.2.jar                   |Botarium                      |botarium                      |2.3.2               |COMMON_SET|Manifest: NOSIGNATURE
		Ponder-Forge-1.20.1-1.0.80.jar                    |Ponder                        |ponder                        |1.0.80              |COMMON_SET|Manifest: NOSIGNATURE
		Grass_Overhaul-Forge-23.10.10-MC1.20.1.jar        |Grass Overhaul                |grassoverhaul                 |23.10.10            |COMMON_SET|Manifest: NOSIGNATURE
		nerb-1.20.1-0.3-FORGE.jar                         |Not Enough Recipe Book        |nerb                          |0.3                 |COMMON_SET|Manifest: NOSIGNATURE
		fabric-convention-tags-v1-1.5.5+fa3d1c0177.jar    |Fabric Convention Tags        |fabric_convention_tags_v1     |1.5.5+fa3d1c0177    |COMMON_SET|Manifest: NOSIGNATURE
		goety-2.5.15.2.jar                                |Goety                         |goety                         |2.5.15.2            |COMMON_SET|Manifest: NOSIGNATURE
		VillagersPlus_3.0_(FORGE)_for_1.20.1.jar          |VillagersPlus                 |villagersplus                 |3.0                 |COMMON_SET|Manifest: NOSIGNATURE
		Powah-5.0.4.jar                                   |Powah                         |powah                         |5.0.4               |COMMON_SET|Manifest: NOSIGNATURE
		bagus_lib-1.20.1-5.3.0.jar                        |Bagus Lib                     |bagus_lib                     |1.20.1-5.3.0        |COMMON_SET|Manifest: NOSIGNATURE
		ResourcePackOverrides-v8.0.1-1.20.1-Forge.jar     |Resource Pack Overrides       |resourcepackoverrides         |8.0.1               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		balm-forge-1.20.1-7.2.1.jar                       |Balm                          |balm                          |7.2.1               |COMMON_SET|Manifest: NOSIGNATURE
		fabric-screen-api-v1-2.0.8+45a670a577.jar         |Fabric Screen API (v1)        |fabric_screen_api_v1          |2.0.8+45a670a577    |COMMON_SET|Manifest: NOSIGNATURE
		JustEnoughResources-1.20.1-1.4.0.247.jar          |Just Enough Resources         |jeresources                   |1.4.0.247           |COMMON_SET|Manifest: NOSIGNATURE
		LeavesBeGone-v8.0.0-1.20.1-Forge.jar              |Leaves Be Gone                |leavesbegone                  |8.0.0               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		geophilic-v2.1.0-mc1.20u1.20.2.jar                |Geophilic                     |geophilic                     |2.1.0-mc1.20u1.20.2 |COMMON_SET|Manifest: NOSIGNATURE
		athena-forge-1.20.1-3.1.1.jar                     |Athena                        |athena                        |3.1.1               |COMMON_SET|Manifest: NOSIGNATURE
		terrablender-bridge-1.11.2+1.20.1.jar             |Connector Extras Terrablender |connectorextras_terrablender_b|1.11.2+1.20.1       |COMMON_SET|Manifest: NOSIGNATURE
		stylecolonies-1.3.jar                             |stylecolonies mod             |stylecolonies                 |1.3                 |COMMON_SET|Manifest: NOSIGNATURE
		lmft-1.0.4+1.20.1-forge.jar                       |Load My F***ing Tags          |lmft                          |1.0.4+1.20.1        |COMMON_SET|Manifest: NOSIGNATURE
		AdvancementPlaques-1.20.1-forge-1.5.1.jar         |Advancement Plaques           |advancementplaques            |1.5.1               |COMMON_SET|Manifest: NOSIGNATURE
		fabric-game-rule-api-v1-1.0.40+683d4da877.jar     |Fabric Game Rule API (v1)     |fabric_game_rule_api_v1       |1.0.40+683d4da877   |COMMON_SET|Manifest: NOSIGNATURE
		Prominent-GLOBAL-MC1.20.1-1.6.0_mapped_srg_1.20.1.|Prominent                     |prominent                     |1.4.2               |COMMON_SET|Manifest: NOSIGNATURE
		ironfurnaces-1.20.1-4.1.3.jar                     |Iron Furnaces                 |ironfurnaces                  |4.1.3               |COMMON_SET|Manifest: NOSIGNATURE
		YungsBridges-1.20-Forge-4.0.3.jar                 |YUNG's Bridges                |yungsbridges                  |1.20-Forge-4.0.3    |COMMON_SET|Manifest: NOSIGNATURE
		resourcefulconfig-forge-1.20.1-2.1.2.jar          |Resourcefulconfig             |resourcefulconfig             |2.1.2               |COMMON_SET|Manifest: NOSIGNATURE
		Ad-Astra-Giselle-Addon-forge-1.20.1-5.8.jar       |Ad Astra: Giselle Addon       |ad_astra_giselle_addon        |5.8                 |COMMON_SET|Manifest: NOSIGNATURE
		variety-1.0.0_mapped_srg_1.20.1.jar               |Variety                       |variety                       |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		frosted-friends-1.20.1-1.0.7.jar                  |Frosted Friends               |frosted_friends               |1.0.7               |COMMON_SET|Manifest: NOSIGNATURE
		curios-forge-5.14.1+1.20.1.jar                    |Curios API                    |curios                        |5.14.1+1.20.1       |COMMON_SET|Manifest: NOSIGNATURE
		Prominent_UI-1.0.0_mapped_srg_1.20.1.jar          |Prominent UI Tweaks           |prominent_ui                  |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		Searchables-forge-1.20.1-1.0.2.jar                |Searchables                   |searchables                   |1.0.2               |COMMON_SET|Manifest: NOSIGNATURE
		Eldritch_End-FORGE-MC1.20.1-0.2.31_mapped_srg_1.20|Eldritch End                  |eldritch_end                  |0.2.31              |COMMON_SET|Manifest: NOSIGNATURE
		Thermal And Space-1.20.1-1.0.1.jar                |Thermal And Space             |thermal_and_space             |1.20.1-1.0.1        |COMMON_SET|Manifest: NOSIGNATURE
		minecells-1.8.3$gimm1q-0.5.3_mapped_srg_1.20.1.jar|gimm1q                        |gimm1q                        |0.5.3               |COMMON_SET|Manifest: NOSIGNATURE
		fabric-entity-events-v1-1.6.0+6274ab9d77.jar      |Fabric Entity Events (v1)     |fabric_entity_events_v1       |1.6.0+6274ab9d77    |COMMON_SET|Manifest: NOSIGNATURE
		YSNS-Forge-MC1.20-1.0.4.jar                       |You Shall Not Spawn!          |ysns                          |1.0.2               |COMMON_SET|Manifest: NOSIGNATURE
		YungsBetterMineshafts-1.20-Forge-4.0.4.jar        |YUNG's Better Mineshafts      |bettermineshafts              |1.20-Forge-4.0.4    |COMMON_SET|Manifest: NOSIGNATURE
		veinmining-forge-1.2.0+1.20.1.jar                 |Vein Mining                   |veinmining                    |1.2.0+1.20.1        |COMMON_SET|Manifest: NOSIGNATURE
		sliceanddice-forge-3.4.1.jar                      |Create Slice & Dice           |sliceanddice                  |3.4.1               |COMMON_SET|Manifest: NOSIGNATURE
		DarkPaintings-Forge-1.20.1-17.0.4.jar             |DarkPaintings                 |darkpaintings                 |17.0.4              |COMMON_SET|Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		fabric-dimensions-v1-2.1.54+8005d10d77.jar        |Fabric Dimensions API (v1)    |fabric_dimensions_v1          |2.1.54+8005d10d77   |COMMON_SET|Manifest: NOSIGNATURE
		elytraslot-forge-6.3.0+1.20.1.jar                 |Elytra Slot                   |elytraslot                    |6.3.0+1.20.1        |COMMON_SET|Manifest: NOSIGNATURE
		Create_Questing-FORGE-1.20.1-1.0.0.jar            |Create Questing               |create_questing               |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		doubledoors-1.20.1-5.1.jar                        |Double Doors                  |doubledoors                   |5.1                 |COMMON_SET|Manifest: NOSIGNATURE
		puzzlesapi-forge-8.0.2.jar                        |Puzzles Api                   |puzzlesapi                    |8.0.2               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		fabric-model-loading-api-v1-1.0.3+6274ab9d77.jar  |Fabric Model Loading API (v1) |fabric_model_loading_api_v1   |1.0.3+6274ab9d77    |COMMON_SET|Manifest: NOSIGNATURE
		jei-1.20.1-forge-15.20.0.110.jar                  |Just Enough Items             |jei                           |15.20.0.110         |COMMON_SET|Manifest: NOSIGNATURE
		multipiston-1.20-1.2.31-ALPHA.jar                 |Multi-Piston                  |multipiston                   |1.20-1.2.31-ALPHA   |COMMON_SET|Manifest: NOSIGNATURE
		The_Graveyard_3.0_(FORGE)_for_1.20.1.jar          |The Graveyard                 |graveyard                     |3.0                 |COMMON_SET|Manifest: NOSIGNATURE
		Mekanism-1.20.1-10.4.16.80.jar                    |Mekanism                      |mekanism                      |10.4.16             |COMMON_SET|Manifest: NOSIGNATURE
		MekanismGenerators-1.20.1-10.4.16.80.jar          |Mekanism: Generators          |mekanismgenerators            |10.4.16             |COMMON_SET|Manifest: NOSIGNATURE
		Stoneworks-v8.0.0-1.20.1-Forge.jar                |Stoneworks                    |stoneworks                    |8.0.0               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		fabric-rendering-v1-3.0.8+66e9a48f77.jar          |Fabric Rendering (v1)         |fabric_rendering_v1           |3.0.8+66e9a48f77    |COMMON_SET|Manifest: NOSIGNATURE
		blossom-blade-1.0.jar                             |Blossom Blade                 |mr_blossom_blade              |1.0                 |COMMON_SET|Manifest: NOSIGNATURE
		fabric-renderer-indigo-1.5.2+b5b2da4177.jar       |Fabric Renderer - Indigo      |fabric_renderer_indigo        |1.5.2+b5b2da4177    |COMMON_SET|Manifest: NOSIGNATURE
		Fallingleaves-1.20.1-2.1.0.jar                    |Falling Leaves                |fallingleaves                 |2.1.0               |COMMON_SET|Manifest: NOSIGNATURE
		Shield_Overhaul-FABRIC-MC1.20.1-1.0.4_mapped_srg_1|Shield Overhaul               |shield_overhaul               |1.0.3               |COMMON_SET|Manifest: NOSIGNATURE
		TravelersBackpack-1.20.1-9.1.7.jar                |Traveler's Backpack           |travelersbackpack             |9.1.7               |COMMON_SET|Manifest: NOSIGNATURE
		NaturesCompass-1.20.1-1.11.2-forge.jar            |Nature's Compass              |naturescompass                |1.20.1-1.11.2-forge |COMMON_SET|Manifest: NOSIGNATURE
		SereneSeasons-1.20.1-9.0.0.43.jar                 |Serene Seasons                |sereneseasons                 |9.0.0.43            |COMMON_SET|Manifest: NOSIGNATURE
		adorabuild-structures-2.3.0-forge-1.20.2.jar      |AdoraBuild: Structures        |adorabuild_structures         |2.3.0               |COMMON_SET|Manifest: NOSIGNATURE
		neruina-1.2.6-forge+1.18.2-1.20.1.jar             |Neruina                       |neruina                       |1.2.6               |COMMON_SET|Manifest: NOSIGNATURE
		geckolib-fabric-compat-1.11.2+1.20.1.jar          |Connector Extras Geckolib-Fabr|connectorextras_geckolib_fabri|1.11.2+1.20.1       |COMMON_SET|Manifest: NOSIGNATURE
		more-immersive-wires-1.20.1-1.1.3.jar             |More Immersive Wires          |more_immersive_wires          |1.1.3               |COMMON_SET|Manifest: NOSIGNATURE
		puzzlesaccessapi-forge-8.0.5.jar                  |Puzzles Access Api            |puzzlesaccessapi              |8.0.5               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		forge-1.20.1-47.1.106-universal.jar               |NeoForge                      |forge                         |47.1.106            |COMMON_SET|Manifest: NOSIGNATURE
		appleskin-forge-mc1.20.1-2.5.1.jar                |AppleSkin                     |appleskin                     |2.5.1+mc1.20.1      |COMMON_SET|Manifest: NOSIGNATURE
		extractinator-forge-1.20-2.2.0.jar                |Extractinator                 |extractinator                 |2.2.0               |COMMON_SET|Manifest: NOSIGNATURE
		chalk-1.20.1-1.6.2.jar                            |Chalk                         |chalk                         |1.6.2               |COMMON_SET|Manifest: NOSIGNATURE
		Log-Begone-neoforge-1.20.1-1.0.9.jar              |Log Begone                    |logbegone                     |1.0.9               |COMMON_SET|Manifest: NOSIGNATURE
		drippyloadingscreen_forge_2.2.4_MC_1.20.1.jar     |Drippy Loading Screen         |drippyloadingscreen           |2.2.4               |COMMON_SET|Manifest: NOSIGNATURE
		alchemistry-1.20.1-2.3.4.jar                      |Alchemistry                   |alchemistry                   |2.3.4               |COMMON_SET|Manifest: NOSIGNATURE
		fabric-api-base-0.4.31+ef105b4977.jar             |Fabric API Base               |fabric_api_base               |0.4.31+ef105b4977   |COMMON_SET|Manifest: NOSIGNATURE
		MouseTweaks-forge-mc1.20-2.25.jar                 |Mouse Tweaks                  |mousetweaks                   |2.25                |COMMON_SET|Manifest: NOSIGNATURE
		bettercombat-fabric-1.8.4+1.20.1_mapped_srg_1.20.1|Better Combat                 |bettercombat                  |1.8.41.20.1         |COMMON_SET|Manifest: NOSIGNATURE
		ImmersiveEngineering-1.20.1-10.0.0-169.jar        |Immersive Engineering         |immersiveengineering          |1.20.1-10.0.0-169   |COMMON_SET|Manifest: 44:39:94:cf:1d:8c:be:3c:7f:a9:ee:f4:1e:63:a5:ac:61:f9:c2:87:d5:5b:d9:d6:8c:b5:3e:96:5d:8e:3f:b7
		NoChatReports-FORGE-1.20.1-v2.2.2.jar             |No Chat Reports               |nochatreports                 |1.20.1-v2.2.2       |COMMON_SET|Manifest: NOSIGNATURE
		MindfulDarkness-v8.0.2-1.20.1-Forge.jar           |Mindful Darkness              |mindfuldarkness               |8.0.2               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		spectrelib-forge-0.13.14+1.20.1.jar               |SpectreLib                    |spectrelib                    |0.13.14+1.20.1      |COMMON_SET|Manifest: NOSIGNATURE
		jei-bridge-1.11.2+1.20.1.jar                      |Connector Extras JEI Bridge   |connectorextras_jei_bridge    |1.11.2+1.20.1       |COMMON_SET|Manifest: NOSIGNATURE
		guccivuitton-1.20.1-0.2.2.jar                     |Gucci & Vuitton Attachments   |guccivuitton                  |0.2.2               |COMMON_SET|Manifest: NOSIGNATURE
		kffmod-4.8.0.jar                                  |Kotlin For Forge              |kotlinforforge                |4.8.0               |COMMON_SET|Manifest: NOSIGNATURE
		Mantle-1.20.1-1.11.63.jar                         |Mantle                        |mantle                        |1.11.63             |COMMON_SET|Manifest: NOSIGNATURE
		Croptopia-1.20.1-FORGE-3.0.2.jar                  |Croptopia                     |croptopia                     |3.0.2               |COMMON_SET|Manifest: NOSIGNATURE
		fabric-item-group-api-v1-4.0.12+c9161c2d77.jar    |Fabric Item Group API (v1)    |fabric_item_group_api_v1      |4.0.12+c9161c2d77   |COMMON_SET|Manifest: NOSIGNATURE
		polymorph-forge-0.49.2+1.20.1.jar                 |Polymorph                     |polymorph                     |0.49.2+1.20.1       |COMMON_SET|Manifest: NOSIGNATURE
		mixininheaven-mc1.17.1-1.20-v0.0.1-hotfix.jar     |MixinInHeaven                 |mixininheaven                 |0.0NONE             |COMMON_SET|Manifest: NOSIGNATURE
		Zeta-1.0-30.jar                                   |Zeta                          |zeta                          |1.0-30              |COMMON_SET|Manifest: NOSIGNATURE
		XaeroPlus-Forge-1.20.1-61-WM1.37.2-MM23.9.3.jar   |XaeroPlus                     |xaeroplus                     |1.20.1              |COMMON_SET|Manifest: NOSIGNATURE
		Xaeros_Minimap_23.9.3_Forge_1.20.jar              |Xaero's Minimap               |xaerominimap                  |23.9.3              |COMMON_SET|Manifest: NOSIGNATURE
		owo-lib-0.11.2+1.20$jankson-1.2.2_mapped_srg_1.20.|jankson                       |blue_endless_jankson          |1.2.2               |COMMON_SET|Manifest: NOSIGNATURE
		oceansdelight-1.0.2-1.20.jar                      |Ocean's Delight               |oceansdelight                 |1.0.2-1.20          |COMMON_SET|Manifest: NOSIGNATURE
		fabric-recipe-api-v1-1.0.21+514a076577.jar        |Fabric Recipe API (v1)        |fabric_recipe_api_v1          |1.0.21+514a076577   |COMMON_SET|Manifest: NOSIGNATURE
		showcaseitem-1.20.1-1.0.jar                       |Showcase Item                 |showcaseitem                  |1.20.1-1.0          |COMMON_SET|Manifest: NOSIGNATURE
		visuality-forge-2.0.2.jar                         |Visuality: Reforged           |visuality                     |2.0.2               |COMMON_SET|Manifest: NOSIGNATURE
		biomemusic-1.20.1-2.2.jar                         |biomemusic mod                |biomemusic                    |1.20.1-2.2          |COMMON_SET|Manifest: NOSIGNATURE
		PuzzlesLib-v8.0.24-1.20.1-Forge.jar               |Puzzles Lib                   |puzzleslib                    |8.0.24              |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		fabric-sound-api-v1-1.0.13+4f23bd8477.jar         |Fabric Sound API (v1)         |fabric_sound_api_v1           |1.0.13+4f23bd8477   |COMMON_SET|Manifest: NOSIGNATURE
		chunksending-1.20.1-2.8.jar                       |chunksending mod              |chunksending                  |1.20.1-2.8          |COMMON_SET|Manifest: NOSIGNATURE
		better-end-4.0.11_mapped_srg_1.20.1.jar           |Better End                    |betterend                     |4.0.11              |COMMON_SET|Manifest: NOSIGNATURE
		aquamirae-6.API15.jar                             |Aquamirae                     |aquamirae                     |6.API15             |COMMON_SET|Manifest: NOSIGNATURE
		xptome-1.20.1-2.1.7.jar                           |XP Tome                       |xpbook                        |2.1.7               |COMMON_SET|Manifest: NOSIGNATURE
		cristellib-1.1.5-forge.jar                        |Cristel Lib                   |cristellib                    |1.1.5               |COMMON_SET|Manifest: NOSIGNATURE
		TreeChop-1.20.1-forge-0.18.3.jar                  |HT's TreeChop                 |treechop                      |0.18.3              |COMMON_SET|Manifest: NOSIGNATURE
		blue_skies-1.20.1-1.3.28.jar                      |Blue Skies                    |blue_skies                    |1.3.28              |COMMON_SET|Manifest: NOSIGNATURE
		YungsBetterWitchHuts-1.20-Forge-3.0.3.jar         |YUNG's Better Witch Huts      |betterwitchhuts               |1.20-Forge-3.0.3    |COMMON_SET|Manifest: NOSIGNATURE
		netherportalfix-forge-1.20-13.0.1.jar             |NetherPortalFix               |netherportalfix               |13.0.1              |COMMON_SET|Manifest: NOSIGNATURE
		geckolib-neoforge-1.20.1-4.4.4.jar                |GeckoLib 4                    |geckolib                      |4.4.4               |COMMON_SET|Manifest: NOSIGNATURE
		creeperoverhaul-3.0.1-forge.jar                   |Creeper Overhaul              |creeperoverhaul               |3.0.1               |COMMON_SET|Manifest: NOSIGNATURE
		ars_nouveau-1.20.1-4.8.1-all.jar                  |Ars Nouveau                   |ars_nouveau                   |4.8.1               |COMMON_SET|Manifest: NOSIGNATURE
		knightsnmages-0.0.6-neo.jar                       |KnightsnMages                 |knightsnmages                 |0.0.6-neo           |COMMON_SET|Manifest: NOSIGNATURE
		ars_elemental-1.20.1-0.6.3.2.jar                  |Ars Elemental                 |ars_elemental                 |1.20.1-0.6.3.2      |COMMON_SET|Manifest: NOSIGNATURE
		minecells-1.8.3$omega-config-base-1.2.3-1.18.1_map|OmegaConfig                   |omega_config                  |1.2.3-1.18.1        |COMMON_SET|Manifest: NOSIGNATURE
		recipeessentials-1.20.1-3.2.jar                   |recipeessentials mod          |recipeessentials              |1.20.1-3.2          |COMMON_SET|Manifest: NOSIGNATURE
		aether-1.20.1-1.0.0-neoforge.jar                  |The Aether                    |aether                        |1.20.1-1.0.0-neoforg|COMMON_SET|Manifest: NOSIGNATURE
		lost_aether_content-1.20.1-1.2.3.jar              |Aether: Lost Content          |lost_aether_content           |1.2.3               |COMMON_SET|Manifest: NOSIGNATURE
		deep_aether-1.20.1-1.0.13.1.jar                   |Deep Aether                   |deep_aether                   |1.20.1-1.0.13.1     |COMMON_SET|Manifest: NOSIGNATURE
		aeroblender-1.20.1-1.0.1-neoforge.jar             |AeroBlender                   |aeroblender                   |1.20.1-1.0.1-neoforg|COMMON_SET|Manifest: NOSIGNATURE
		aether-redux-1.3.4-1.20.1-neoforge.jar            |The Aether: Redux             |aether_redux                  |1.20.1              |COMMON_SET|Manifest: NOSIGNATURE
		connectivity-1.20.1-4.9.jar                       |Connectivity Mod              |connectivity                  |1.20.1-4.9          |COMMON_SET|Manifest: NOSIGNATURE
		kleeslabs-forge-1.20-15.0.0.jar                   |KleeSlabs                     |kleeslabs                     |15.0.0              |COMMON_SET|Manifest: NOSIGNATURE
		ars_scalaes-1.20.1-1.10.1-alpha.jar               |Ars Nouveau Scaling Compats   |ars_scalaes                   |1.20.1-1.10.1-alpha |COMMON_SET|Manifest: NOSIGNATURE
		XaerosWorldMap_1.37.2_Forge_1.20.jar              |Xaero's World Map             |xaeroworldmap                 |1.37.2              |COMMON_SET|Manifest: NOSIGNATURE
		Controlling-forge-1.20.1-12.0.2.jar               |Controlling                   |controlling                   |12.0.2              |COMMON_SET|Manifest: NOSIGNATURE
		citadel-2.5.4-1.20.1.jar                          |Citadel                       |citadel                       |2.5.4               |COMMON_SET|Manifest: NOSIGNATURE
		L_Enders_Cataclysm-1.90 -1.20.1.jar               |Cataclysm Mod                 |cataclysm                     |1.0                 |COMMON_SET|Manifest: NOSIGNATURE
		iceandfire-2.1.13-1.20.1-beta-4.jar               |Ice and Fire                  |iceandfire                    |2.1.13-1.20.1-beta-4|COMMON_SET|Manifest: NOSIGNATURE
		fabric-data-attachment-api-v1-1.0.0+30ef839e77.jar|Fabric Data Attachment API (v1|fabric_data_attachment_api_v1 |1.0.0+30ef839e77    |COMMON_SET|Manifest: NOSIGNATURE
		mixinextras-forge-0.2.0.jar                       |MixinExtras                   |mixinextras                   |0.2.0               |COMMON_SET|Manifest: NOSIGNATURE
		emitrades-forge-1.2.1+mc1.20.1.jar                |EMI Trades                    |emitrades                     |1.2.1+mc1.20.1      |COMMON_SET|Manifest: NOSIGNATURE
		twigs-1.20.1-3.1.0-forge.jar                      |Twigs                         |twigs                         |1.20.1-3.1.0        |COMMON_SET|Manifest: NOSIGNATURE
		piglinsafety-mc1.17-1.20-v0.0.2.jar               |PiglinSafety                  |piglinsafety                  |0.0.2               |COMMON_SET|Manifest: NOSIGNATURE
		relics-1.20.1-0.4.8.6.jar                         |Relics                        |relics                        |0.4.8.6             |COMMON_SET|Manifest: NOSIGNATURE
		bclib-3.0.14$wunderlib-1.1.5_mapped_srg_1.20.1.jar|WunderLib                     |wunderlib                     |1.1.5               |COMMON_SET|Manifest: NOSIGNATURE
		wares-1.20.1-1.2.7.jar                            |Wares                         |wares                         |1.2.7               |COMMON_SET|Manifest: NOSIGNATURE
		Steam_Rails-1.6.11-alpha+forge-mc1.20.1.jar       |Create: Steam 'n' Rails       |railways                      |1.6.11-alpha+forge-m|COMMON_SET|Manifest: NOSIGNATURE
		dummmmmmy-1.20-1.8.3.jar                          |MmmMmmMmmmmm                  |dummmmmmy                     |1.20-1.8.3          |COMMON_SET|Manifest: NOSIGNATURE
		bclib-3.0.14_mapped_srg_1.20.1.jar                |BCLib                         |bclib                         |3.0.14              |COMMON_SET|Manifest: NOSIGNATURE
		fabric-content-registries-v0-4.0.11+a670df1e77.jar|Fabric Content Registries (v0)|fabric_content_registries_v0  |4.0.11+a670df1e77   |COMMON_SET|Manifest: NOSIGNATURE
		twilightforest-1.20.1-4.3.2145-universal.jar      |The Twilight Forest           |twilightforest                |4.3.2145            |COMMON_SET|Manifest: NOSIGNATURE
		mob_grinding_utils-1.20.1-1.0.3.jar               |Mob Grinding Utils            |mob_grinding_utils            |1.20.1-1.0.3        |COMMON_SET|Manifest: NOSIGNATURE
		FarmersDelight-1.20.1-1.2.3.jar                   |Farmer's Delight              |farmersdelight                |1.20.1-1.2.3        |COMMON_SET|Manifest: NOSIGNATURE
		corn_delight-1.1.8-1.20.1.jar                     |Corn Delight                  |corn_delight                  |1.1.8-1.20.1        |COMMON_SET|Manifest: NOSIGNATURE
		tofudelight-1.20.1-3.2.0.jar                      |TofuDelight                   |tofudelight                   |1.20.1-3.2.0        |COMMON_SET|Manifest: NOSIGNATURE
		chefs-delight-1.0.3-forge-1.20.1.jar              |Chefs Delight                 |chefsdelight                  |1.0.3-forge-1.20.1  |COMMON_SET|Manifest: NOSIGNATURE
		cuisinedelight-1.1.12.jar                         |Cuisine Delight               |cuisinedelight                |1.1.12              |COMMON_SET|Manifest: NOSIGNATURE
		refinedpolymorph-0.1.0-1.20.1.jar                 |Refined Polymorphism          |refinedpolymorph              |0.1.0-1.20.1        |COMMON_SET|Manifest: NOSIGNATURE
		basket-1.20.1-1.0.0.jar                           |baskets                       |baskets                       |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		endersdelight-1.20.1-1.0.3.jar                    |Ender's Delight               |endersdelight                 |1.0.3               |COMMON_SET|Manifest: NOSIGNATURE
		cataclysmiccombat 1.1.jar                         |Cataclysmic Combat            |cataclysmiccombat             |1.1                 |COMMON_SET|Manifest: NOSIGNATURE
		MekanismAdditions-1.20.1-10.4.16.80.jar           |Mekanism: Additions           |mekanismadditions             |10.4.16             |COMMON_SET|Manifest: NOSIGNATURE
		endrem_forge-5.2.3-R-1.20.X.jar                   |End Remastered                |endrem                        |5.2.3-R-1.20.1      |COMMON_SET|Manifest: NOSIGNATURE
		mining_dimension-1.20.1-1.0.4.jar                 |Mining World                  |mining_dimension              |1.20.1-1.0.4        |COMMON_SET|Manifest: NOSIGNATURE
		reach-entity-attributes-2.4.0.jar                 |Reach Entity Attributes       |reach_entity_attributes       |2.4.0               |COMMON_SET|Manifest: NOSIGNATURE
		ReBalance-FORGE-1.0.0_mapped_srg_1.20.1.jar       |ReBalance                     |rebalance                     |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		dungeons_enhanced-1.20.1-5.2.2.jar                |Dungeons Enhanced             |dungeons_enhanced             |5.2.2               |COMMON_SET|Manifest: NOSIGNATURE
		Patchouli-1.20.1-83-FORGE.jar                     |Patchouli                     |patchouli                     |1.20.1-83-FORGE     |COMMON_SET|Manifest: NOSIGNATURE
		ars_ocultas-1.20.1-1.1.0-all.jar                  |Ars Ocultas                   |ars_ocultas                   |1.1.0               |COMMON_SET|Manifest: NOSIGNATURE
		despawn_tweaker-1.20.1-0.0.5.jar                  |DespawnTweaker                |despawn_tweaker               |1.20.1-0.0.5        |COMMON_SET|Manifest: NOSIGNATURE
		collective-1.20.1-7.16.jar                        |Collective                    |collective                    |7.16                |COMMON_SET|Manifest: NOSIGNATURE
		BetterThirdPerson-Forge-1.20-1.9.0.jar            |Better Third Person           |betterthirdperson             |1.9.0               |COMMON_SET|Manifest: NOSIGNATURE
		YungsBetterStrongholds-1.20-Forge-4.0.3.jar       |YUNG's Better Strongholds     |betterstrongholds             |1.20-Forge-4.0.3    |COMMON_SET|Manifest: NOSIGNATURE
		resourcefullib-forge-1.20.1-2.1.20.jar            |Resourceful Lib               |resourcefullib                |2.1.20              |COMMON_SET|Manifest: NOSIGNATURE
		MekanismTools-1.20.1-10.4.16.80.jar               |Mekanism: Tools               |mekanismtools                 |10.4.16             |COMMON_SET|Manifest: NOSIGNATURE
		deeperdarker-forge-1.20.1-1.2.0.jar               |Deeper and Darker             |deeperdarker                  |1.2.0               |COMMON_SET|Manifest: NOSIGNATURE
		BoatBreakFix-Universal-1.0.2.jar                  |Boat Break Fix                |boatbreakfix                  |1.0.2               |COMMON_SET|Manifest: NOSIGNATURE
		architectury-9.2.14-forge.jar                     |Architectury                  |architectury                  |9.2.14              |COMMON_SET|Manifest: NOSIGNATURE
		[1.20.1-forge]-Epic-Knights-8.11.jar              |Epic Knights Mod              |magistuarmory                 |8.11                |COMMON_SET|Manifest: NOSIGNATURE
		simplyswords-forge-1.51.5-1.20.1.jar              |Simply Swords                 |simplyswords                  |1.51.5-1.20.1       |COMMON_SET|Manifest: NOSIGNATURE
		gardens-of-the-dead-forge-4.0.1.jar               |Gardens of the Dead           |gardens_of_the_dead           |4.0.1               |COMMON_SET|Manifest: NOSIGNATURE
		allthetrims-3.2.0-forge+1.20.1.jar                |AllTheTrims                   |allthetrims                   |3.2.0               |COMMON_SET|Manifest: NOSIGNATURE
		ftb-library-forge-2001.1.4.jar                    |FTB Library                   |ftblibrary                    |2001.1.4            |COMMON_SET|Manifest: NOSIGNATURE
		ftb-teams-forge-2001.1.4.jar                      |FTB Teams                     |ftbteams                      |2001.1.4            |COMMON_SET|Manifest: NOSIGNATURE
		cc-tweaked-1.20.1-forge-1.108.1.jar               |CC: Tweaked                   |computercraft                 |1.108.1             |COMMON_SET|Manifest: NOSIGNATURE
		fabric-loot-api-v2-1.2.1+eb28f93e77.jar           |Fabric Loot API (v2)          |fabric_loot_api_v2            |1.2.1+eb28f93e77    |COMMON_SET|Manifest: NOSIGNATURE
		ConnectorExtras-1.11.2+1.20.1.jar                 |Connector Extras              |connectorextras               |1.11.2+1.20.1       |COMMON_SET|Manifest: NOSIGNATURE
		fabric-networking-api-v1-1.3.11+503a202477.jar    |Fabric Networking API (v1)    |fabric_networking_api_v1      |1.3.11+503a202477   |COMMON_SET|Manifest: NOSIGNATURE
		Towns-and-Towers-1.11-Fabric+Forge.jar            |Towns and Towers              |t_and_t                       |0.0NONE             |COMMON_SET|Manifest: NOSIGNATURE
		YeetusExperimentus-Forge-2.3.1-build.6+mc1.20.1.ja|Yeetus Experimentus           |yeetusexperimentus            |2.3.1-build.6+mc1.20|COMMON_SET|Manifest: NOSIGNATURE
		fabric-lifecycle-events-v1-2.2.22+afab492177.jar  |Fabric Lifecycle Events (v1)  |fabric_lifecycle_events_v1    |2.2.22+afab492177   |COMMON_SET|Manifest: NOSIGNATURE
		fm_audio_extension_forge_1.1.1_MC_1.20.jar        |FancyMenu Audio Extension     |fmextension_audio             |1.1.1               |COMMON_SET|Manifest: NOSIGNATURE
		TradingPost-v8.0.1-1.20.1-Forge.jar               |Trading Post                  |tradingpost                   |8.0.1               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		inventorysorter-1.20.1-23.0.1.jar                 |Simple Inventory Sorter       |inventorysorter               |23.0.1              |COMMON_SET|Manifest: NOSIGNATURE
		BHMenu-Forge-1.20.1-2.4.1.jar                     |BHMenu                        |bhmenu                        |2.4.1               |COMMON_SET|Manifest: NOSIGNATURE
		potacore-0.1.1-universal.jar                      |Potacore                      |potacore                      |0.1.1-universal     |COMMON_SET|Manifest: NOSIGNATURE
		owo-lib-0.11.2+1.20_mapped_srg_1.20.1.jar         |oωo                           |owo                           |0.11.21.20          |COMMON_SET|Manifest: NOSIGNATURE
		amendments-1.20-1.1.11.jar                        |Amendments                    |amendments                    |1.20-1.1.11         |COMMON_SET|Manifest: NOSIGNATURE
		sophisticatedstorage-1.20.1-1.3.51.1182.jar       |Sophisticated Storage         |sophisticatedstorage          |1.3.51.1182         |COMMON_SET|Manifest: NOSIGNATURE
		item-filters-forge-2001.1.0-build.59.jar          |Item Filters                  |itemfilters                   |2001.1.0-build.59   |COMMON_SET|Manifest: NOSIGNATURE
		ftb-quests-forge-2001.3.0.jar                     |FTB Quests                    |ftbquests                     |2001.3.0            |COMMON_SET|Manifest: NOSIGNATURE
		ftb-xmod-compat-forge-2.1.0.jar                   |FTB XMod Compat               |ftbxmodcompat                 |2.1.0               |COMMON_SET|Manifest: NOSIGNATURE
		tacz-1.20.1-1.1.6-hotfix.jar                      |Timeless & Classics Guns: Zero|tacz                          |1.1.6-hotfix        |COMMON_SET|Manifest: NOSIGNATURE
		SimpleRPC-Universal-3.3.2.jar                     |Simple RPC                    |simplerpc                     |3.3.2               |COMMON_SET|Manifest: NOSIGNATURE
		Ping-Wheel-1.6.1-forge-1.20.1.jar                 |Ping Wheel                    |pingwheel                     |1.6.1               |COMMON_SET|Manifest: NOSIGNATURE
		GeckoLibOculusCompat-Forge-1.0.1.jar              |GeckoLibIrisCompat            |geckoanimfix                  |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		create-1.20.1-6.0.6.jar                           |Create                        |create                        |6.0.6               |COMMON_SET|Manifest: NOSIGNATURE
		ars_creo-1.20.1-4.0.1.jar                         |Ars Creo                      |ars_creo                      |4.0.1               |ERROR     |Manifest: NOSIGNATURE
		some-assembly-required-1.20.1-4.2.0.jar           |Some Assembly Required        |some_assembly_required        |1.20.1-4.2.0        |COMMON_SET|Manifest: NOSIGNATURE
		Delightful-1.20.1-3.4.2.jar                       |Delightful                    |delightful                    |3.4.2               |COMMON_SET|Manifest: NOSIGNATURE
		waystones-forge-1.20-14.0.2.jar                   |Waystones                     |waystones                     |14.0.2              |COMMON_SET|Manifest: NOSIGNATURE
		MonsterPlus-Forge1.20.1-v1.1.6.1.jar              |Monster Plus                  |monsterplus                   |1.0                 |COMMON_SET|Manifest: NOSIGNATURE
		Structory_1.20.1_v1.3.2.jar                       |Structory                     |structory                     |1.3.2               |COMMON_SET|Manifest: NOSIGNATURE
		comforts-forge-6.3.4+1.20.1.jar                   |Comforts                      |comforts                      |6.3.4+1.20.1        |COMMON_SET|Manifest: NOSIGNATURE
		fabric-mining-level-api-v1-2.1.50+561530ec77.jar  |Fabric Mining Level API (v1)  |fabric_mining_level_api_v1    |2.1.50+561530ec77   |COMMON_SET|Manifest: NOSIGNATURE
		alternate_current-mc1.20-1.7.0.jar                |Alternate Current             |alternate_current             |1.7.0               |COMMON_SET|Manifest: NOSIGNATURE
		Shield_Overhaul-FABRIC-MC1.20.1-1.0.4$player-anima|Player Animator               |player_animator               |1.0.2-rc11.20       |COMMON_SET|Manifest: NOSIGNATURE
		redirectionor-1.20.1-4.3.2-forge.jar              |Redirectionor                 |redirectionor                 |1.20.1-4.3.2        |COMMON_SET|Manifest: NOSIGNATURE
		Dungeon Crawl-1.20.1-2.3.14.jar                   |Dungeon Crawl                 |dungeoncrawl                  |2.3.14              |COMMON_SET|Manifest: NOSIGNATURE
		create-confectionery1.20.1_v1.1.0.jar             |Create Confectionery          |create_confectionery          |1.1.0               |COMMON_SET|Manifest: NOSIGNATURE
		mighty_mail-forge-1.20.1-1.0.14.jar               |Mighty Mail                   |mighty_mail                   |1.0.14              |COMMON_SET|Manifest: 0d:78:5f:44:c0:47:0c:8c:e2:63:a3:04:43:d4:12:7d:b0:7c:35:37:dc:40:b1:c1:98:ec:51:eb:3b:3c:45:99
		YungsBetterDesertTemples-1.20-Forge-3.0.3.jar     |YUNG's Better Desert Temples  |betterdeserttemples           |1.20-Forge-3.0.3    |COMMON_SET|Manifest: NOSIGNATURE
		netherdepthsupgrade-3.1.2-1.20.jar                |Nether Depths Upgrade         |netherdepthsupgrade           |3.1.2-1.20          |COMMON_SET|Manifest: NOSIGNATURE
		Block Swap-forge-1.20.1-5.0.0.0.jar               |Block Swap                    |blockswap                     |5.0.0.0             |COMMON_SET|Manifest: NOSIGNATURE
		minecells-1.8.3_mapped_srg_1.20.1.jar             |Mine Cells                    |minecells                     |1.8.3               |COMMON_SET|Manifest: NOSIGNATURE
		fabric-transitive-access-wideners-v1-4.3.1+1880499|Fabric Transitive Access Widen|fabric_transitive_access_widen|4.3.1+1880499877    |COMMON_SET|Manifest: NOSIGNATURE
		illagersweararmor-1.20-1.3.2.jar                  |Illagers Wear Armor           |zillagersweararmor            |1.20-1.3.2          |COMMON_SET|Manifest: NOSIGNATURE
		client-1.20.1-20230612.114412-srg.jar             |Minecraft                     |minecraft                     |1.20.1              |COMMON_SET|Manifest: a1:d4:5e:04:4f:d3:d6:e0:7b:37:97:cf:77:b0:de:ad:4a:47:ce:8c:96:49:5f:0a:cf:8c:ae:b2:6d:4b:8a:3f
		cofh_core-1.20.1-11.0.0.51.jar                    |CoFH Core                     |cofh_core                     |11.0.0              |COMMON_SET|Manifest: NOSIGNATURE
		thermal_core-1.20.1-11.0.2.18.jar                 |Thermal Series                |thermal                       |11.0.2              |COMMON_SET|Manifest: NOSIGNATURE
		thermal_integration-1.20.1-11.0.0.23.jar          |Thermal Integration           |thermal_integration           |11.0.0              |COMMON_SET|Manifest: NOSIGNATURE
		thermal_cultivation-1.20.1-11.0.0.22.jar          |Thermal Cultivation           |thermal_cultivation           |11.0.0              |COMMON_SET|Manifest: NOSIGNATURE
		DramaticDoors-QuiFabrge-1.20.1-3.1.5.jar          |Dramatic Doors                |dramaticdoors                 |1.20.1-3.1.5        |COMMON_SET|Manifest: NOSIGNATURE
		thermal_innovation-1.20.1-11.0.0.21.jar           |Thermal Innovation            |thermal_innovation            |11.0.0              |COMMON_SET|Manifest: NOSIGNATURE
		thermal_foundation-1.20.1-11.0.2.64.jar           |Thermal Foundation            |thermal_foundation            |11.0.2              |COMMON_SET|Manifest: NOSIGNATURE
		thermal_locomotion-1.20.1-11.0.0.17.jar           |Thermal Locomotion            |thermal_locomotion            |11.0.0              |COMMON_SET|Manifest: NOSIGNATURE
		thermal_dynamics-1.20.1-11.0.0.21.jar             |Thermal Dynamics              |thermal_dynamics              |11.0.0              |COMMON_SET|Manifest: NOSIGNATURE
		thermal_expansion-1.20.1-11.0.0.27.jar            |Thermal Expansion             |thermal_expansion             |11.0.0              |COMMON_SET|Manifest: NOSIGNATURE
		alexscaves-1.1.4.jar                              |Alex's Caves                  |alexscaves                    |1.1.4               |COMMON_SET|Manifest: NOSIGNATURE
		EnchantmentDescriptions-Forge-1.20.1-17.0.9.jar   |EnchantmentDescriptions       |enchdesc                      |17.0.9              |COMMON_SET|Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		moonlight-1.20-2.11.9-forge.jar                   |Moonlight Library             |moonlight                     |1.20-2.11.9         |COMMON_SET|Manifest: NOSIGNATURE
		titanium-1.20.1-3.8.24.jar                        |Titanium                      |titanium                      |3.8.24              |COMMON_SET|Manifest: NOSIGNATURE
		RegionsUnexploredForge-0.5.2+1.20.1.jar           |Regions Unexplored            |regions_unexplored            |0.5.2               |COMMON_SET|Manifest: NOSIGNATURE
		MagnumTorch-v8.0.0-1.20.1-Forge.jar               |Magnum Torch                  |magnumtorch                   |8.0.0               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		mixinsquared-forge-0.1.1.jar                      |MixinSquared                  |mixinsquared                  |0.1.1               |COMMON_SET|Manifest: NOSIGNATURE
		Jade-1.20.1-forge-11.6.3.jar                      |Jade                          |jade                          |11.6.3              |COMMON_SET|Manifest: NOSIGNATURE
		appliedenergistics2-forge-15.0.23.jar             |Applied Energistics 2         |ae2                           |15.0.23             |COMMON_SET|Manifest: NOSIGNATURE
		ae2wtlib-15.2.2-forge.jar                         |AE2WTLib                      |ae2wtlib                      |15.2.2-forge        |COMMON_SET|Manifest: NOSIGNATURE
		AE2-Things-1.2.1.jar                              |AE2 Things                    |ae2things                     |1.2.1               |COMMON_SET|Manifest: NOSIGNATURE
		snowyspirit-1.20-3.0.6.jar                        |Snowy Spirit                  |snowyspirit                   |1.20-3.0.6          |COMMON_SET|Manifest: NOSIGNATURE
		friendsandfoes-beekeeperhut-forge-mc1.20-1.3.0.jar|Friends&Foes - Beekeeper Hut  |beekeeperhut                  |1.3.0               |COMMON_SET|Manifest: NOSIGNATURE
		theurgy-1.20.1-1.6.4.jar                          |Theurgy                       |theurgy                       |1.6.4               |COMMON_SET|Manifest: NOSIGNATURE
		nethersdelight-1.20.1-4.0.jar                     |Nether's Delight              |nethersdelight                |1.20.1-4.0          |COMMON_SET|Manifest: NOSIGNATURE
		BarteringStation-v8.0.0-1.20.1-Forge.jar          |Bartering Station             |barteringstation              |8.0.0               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		Iceberg-1.20.1-forge-1.1.18.jar                   |Iceberg                       |iceberg                       |1.1.18              |COMMON_SET|Manifest: NOSIGNATURE
		Quark-4.0-462.jar                                 |Quark                         |quark                         |4.0-462             |COMMON_SET|Manifest: NOSIGNATURE
		supplementaries-1.20-2.8.7.jar                    |Supplementaries               |supplementaries               |1.20-2.8.7          |COMMON_SET|Manifest: NOSIGNATURE
		chemlib-1.20.1-2.0.18.jar                         |ChemLib                       |chemlib                       |2.0.18              |COMMON_SET|Manifest: NOSIGNATURE
		obsidianui-0.1.2+1.20.1.jar                       |ObsidianUI                    |spruceui                      |0.1.2+1.20.1        |COMMON_SET|Manifest: NOSIGNATURE
		JustEnoughMekanismMultiblocks-1.20.1-4.10.jar     |Just Enough Mekanism Multibloc|jei_mekanism_multiblocks      |4.10                |COMMON_SET|Manifest: NOSIGNATURE
		modonomicon-1.20.1-forge-1.39.0.jar               |Modonomicon                   |modonomicon                   |1.39.0              |COMMON_SET|Manifest: NOSIGNATURE
		cryonicconfig-forge-1.0.0+mc1.20.1.jar            |Cryonic Config                |cryonicconfig                 |1.0.0+mc1.20.1      |COMMON_SET|Manifest: NOSIGNATURE
		coroutil-forge-1.20.1-1.3.6.jar                   |CoroUtil                      |coroutil                      |1.20.1-1.3.6        |COMMON_SET|Manifest: NOSIGNATURE
		YOSBY-Forge-1.1.0.jar                             |yosby                         |yosby                         |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		chisel-forge-2.0.0+mc1.20.1.jar                   |Chisel Reborn                 |chisel                        |2.0.0+mc1.20.1      |COMMON_SET|Manifest: NOSIGNATURE
		convenientdecor-0.3.0_mapped_srg_1.20.1.jar       |Convenient Decor              |convenientdecor               |0.3.0               |COMMON_SET|Manifest: NOSIGNATURE
		CrabbersDelight-1.20.1-1.1.3a.jar                 |Crabber's Delight             |crabbersdelight               |1.1.3a              |COMMON_SET|Manifest: NOSIGNATURE
		expandability-forge-9.0.0.jar                     |ExpandAbility                 |expandability                 |9.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		emi-bridge-1.11.2+1.20.1.jar                      |Connector Extras EMI Bridge   |connectorextras_emi_bridge    |1.11.2+1.20.1       |COMMON_SET|Manifest: NOSIGNATURE
		fabric-data-generation-api-v1-12.3.4+369cb3a477.ja|Fabric Data Generation API (v1|fabric_data_generation_api_v1 |12.3.4+369cb3a477   |COMMON_SET|Manifest: NOSIGNATURE
		fabric-events-interaction-v0-0.6.2+0d0bd5a777.jar |Fabric Events Interaction (v0)|fabric_events_interaction_v0  |0.6.2+0d0bd5a777    |COMMON_SET|Manifest: NOSIGNATURE
	Flywheel Backend: flywheel:off
	Crash Report UUID: 700f3d25-fe42-4ebc-b3f5-175c830a8d80
	FML: 47.1
	NeoForge: net.neoforged:47.1.106
