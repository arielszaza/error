# error


The game crashed whilst initializing game
Error: org.spongepowered.asm.mixin.transformer.throwables.MixinTransformerError: An unexpected critical error was encountered




---- Minecraft Crash Report ----
// I let you down. Sorry :(

Time: 2024-03-14 14:30:14
Description: Initializing game

org.spongepowered.asm.mixin.transformer.throwables.MixinTransformerError: An unexpected critical error was encountered
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.applyMixins(MixinProcessor.java:392) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.MixinTransformer.transformClass(MixinTransformer.java:250) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.service.modlauncher.MixinTransformationHandler.processClass(MixinTransformationHandler.java:131) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.launch.MixinLaunchPluginLegacy.processClass(MixinLaunchPluginLegacy.java:131) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at cpw.mods.modlauncher.serviceapi.ILaunchPluginService.processClassWithFlags(ILaunchPluginService.java:156) ~[modlauncher-10.0.9.jar:10.0.9+10.0.9+main.dcd20f30] {}
	at cpw.mods.modlauncher.LaunchPluginHandler.offerClassNodeToPlugins(LaunchPluginHandler.java:88) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.ClassTransformer.transform(ClassTransformer.java:120) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.TransformingClassLoader.maybeTransformClassBytes(TransformingClassLoader.java:50) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.cl.ModuleClassLoader.readerToClass(ModuleClassLoader.java:113) ~[securejarhandler-2.1.10.jar:?] {}
	at cpw.mods.cl.ModuleClassLoader.lambda$findClass$15(ModuleClassLoader.java:219) ~[securejarhandler-2.1.10.jar:?] {}
	at cpw.mods.cl.ModuleClassLoader.loadFromModule(ModuleClassLoader.java:229) ~[securejarhandler-2.1.10.jar:?] {}
	at cpw.mods.cl.ModuleClassLoader.findClass(ModuleClassLoader.java:219) ~[securejarhandler-2.1.10.jar:?] {}
	at cpw.mods.cl.ModuleClassLoader.loadClass(ModuleClassLoader.java:135) ~[securejarhandler-2.1.10.jar:?] {}
	at java.lang.ClassLoader.loadClass(ClassLoader.java:525) ~[?:?] {}
	at me.jellysquid.mods.sodium.client.SodiumClientMod.loadConfig(SodiumClientMod.java:53) ~[rubidium-mc1.20.1-0.7.1a.jar%23572!/:?] {re:mixin,re:classloading}
	at me.jellysquid.mods.sodium.client.SodiumClientMod.<clinit>(SodiumClientMod.java:22) ~[rubidium-mc1.20.1-0.7.1a.jar%23572!/:?] {re:mixin,re:classloading}
	at com.mojang.blaze3d.platform.Window.redirect$zfh000$wrapGlfwCreateWindow(Window.java:535) ~[client-1.20.1-20230612.114412-srg.jar%23644!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:rubidium.mixins.json:workarounds.context_creation.WindowMixin,pl:mixin:APP:mixins.essential.json:client.gui.Mixin_ScaleForMainMenu,pl:mixin:APP:mixins.oculus.json:MixinWindow,pl:mixin:A,pl:runtimedistcleaner:A}
	at com.mojang.blaze3d.platform.Window.<init>(Window.java:86) ~[client-1.20.1-20230612.114412-srg.jar%23644!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:rubidium.mixins.json:workarounds.context_creation.WindowMixin,pl:mixin:APP:mixins.essential.json:client.gui.Mixin_ScaleForMainMenu,pl:mixin:APP:mixins.oculus.json:MixinWindow,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.VirtualScreen.m_110872_(VirtualScreen.java:21) ~[client-1.20.1-20230612.114412-srg.jar%23644!/:?] {re:classloading}
	at net.minecraft.client.Minecraft.<init>(Minecraft.java:440) ~[client-1.20.1-20230612.114412-srg.jar%23644!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,xf:fml:xaerominimap:xaero_minecraftclient,xf:fml:xaeroworldmap:xaero_wm_minecraftclient,pl:runtimedistcleaner:A,re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,xf:fml:xaerominimap:xaero_minecraftclient,xf:fml:xaeroworldmap:xaero_wm_minecraftclient,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,xf:fml:xaerominimap:xaero_minecraftclient,xf:fml:xaeroworldmap:xaero_wm_minecraftclient,pl:mixin:APP:alexscaves.mixins.json:client.MinecraftMixin,pl:mixin:APP:dynamiclightsreforged.mixins.json:MinecraftClientMixin,pl:mixin:APP:rubidium.mixins.json:core.MinecraftClientMixin,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:mixins.oculus.json:MixinMinecraft_PipelineManagement,pl:mixin:APP:majruszlibrary-common.mixins.json:MixinMinecraft,pl:mixin:APP:fastload.mixins.json:client.MinecraftMixin,pl:mixin:APP:fallingleaves.mixins.json:MinecraftClientMixin,pl:mixin:APP:biomemusic.mixins.json:ClientMusicChoiceMixin,pl:mixin:APP:mixins.satin.client.json:event.MinecraftClientMixin,pl:mixin:APP:witherstormmod.mixins.json:MixinMinecraft,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:azurelib.forge.mixins.json:MinecraftMixin,pl:mixin:APP:mixins.essential.json:client.Mixin_RunEssentialTasks,pl:mixin:APP:mixins.essential.json:client.MixinMinecraft,pl:mixin:APP:mixins.essential.json:client.gui.Mixin_FixKeybindUnpressedInEmoteWheel,pl:mixin:APP:mixins.essential.json:client.gui.Mixin_RecalculateMenuScale,pl:mixin:APP:mixins.essential.json:compatibility.vanilla.Mixin_WorkaroundBrokenFramebufferBlitBlending,pl:mixin:APP:mixins.essential.json:feature.emote.Mixin_AllowMovementDuringEmoteWheel_HandleKeybinds,pl:mixin:APP:mixins.essential.json:feature.skin_overwrites.Mixin_InstallTrustingServicesKeyInfo,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:182) ~[forge-47.2.1.jar:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:smoothboot.mixins.json:client.MainMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:111) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:99) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$makeService$0(CommonClientLaunchHandler.java:25) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:108) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:78) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}
Caused by: org.spongepowered.asm.mixin.throwables.MixinApplyError: Mixin [mixins.oculus.compat.sodium.json:options.MixinSodiumGameOptions] from phase [DEFAULT] in config [mixins.oculus.compat.sodium.json] FAILED during APPLY
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.handleMixinError(MixinProcessor.java:636) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.handleMixinApplyError(MixinProcessor.java:588) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.applyMixins(MixinProcessor.java:379) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	... 35 more
Caused by: org.spongepowered.asm.mixin.injection.throwables.InvalidInjectionException: Critical injection failure: @Inject annotation on iris$writeIrisConfig could not find any targets matching 'writeToDisk' in me.jellysquid.mods.sodium.client.gui.SodiumGameOptions. Using refmap sodiumCompatibility-oculus-mixins-refmap.json [PREINJECT Applicator Phase -> mixins.oculus.compat.sodium.json:options.MixinSodiumGameOptions -> Prepare Injections ->  -> handler$bcc000$iris$writeIrisConfig(Lorg/spongepowered/asm/mixin/injection/callback/CallbackInfo;)V -> Parse]
	at org.spongepowered.asm.mixin.injection.struct.InjectionInfo.validateTargets(InjectionInfo.java:656) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.injection.struct.InjectionInfo.findTargets(InjectionInfo.java:587) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.injection.struct.InjectionInfo.readAnnotation(InjectionInfo.java:330) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.injection.struct.InjectionInfo.<init>(InjectionInfo.java:316) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.injection.struct.InjectionInfo.<init>(InjectionInfo.java:308) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.injection.struct.CallbackInjectionInfo.<init>(CallbackInjectionInfo.java:46) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at jdk.internal.reflect.GeneratedConstructorAccessor36.newInstance(Unknown Source) ~[?:?] {}
	at jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45) ~[?:?] {}
	at java.lang.reflect.Constructor.newInstanceWithCaller(Constructor.java:499) ~[?:?] {}
	at java.lang.reflect.Constructor.newInstance(Constructor.java:480) ~[?:?] {}
	at org.spongepowered.asm.mixin.injection.struct.InjectionInfo$InjectorEntry.create(InjectionInfo.java:149) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.injection.struct.InjectionInfo.parse(InjectionInfo.java:708) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.MixinTargetContext.prepareInjections(MixinTargetContext.java:1311) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.MixinApplicatorStandard.prepareInjections(MixinApplicatorStandard.java:1042) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.MixinApplicatorStandard.applyMixin(MixinApplicatorStandard.java:393) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.MixinApplicatorStandard.apply(MixinApplicatorStandard.java:325) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.TargetClassContext.apply(TargetClassContext.java:383) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.TargetClassContext.applyMixins(TargetClassContext.java:365) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.applyMixins(MixinProcessor.java:363) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	... 35 more


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Render thread
Stacktrace:
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.applyMixins(MixinProcessor.java:392) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.mixin.transformer.MixinTransformer.transformClass(MixinTransformer.java:250) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.service.modlauncher.MixinTransformationHandler.processClass(MixinTransformationHandler.java:131) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at org.spongepowered.asm.launch.MixinLaunchPluginLegacy.processClass(MixinLaunchPluginLegacy.java:131) ~[mixin-0.8.5.jar:0.8.5+Jenkins-b310.git-155314e6e91465dad727e621a569906a410cd6f4] {}
	at cpw.mods.modlauncher.serviceapi.ILaunchPluginService.processClassWithFlags(ILaunchPluginService.java:156) ~[modlauncher-10.0.9.jar:10.0.9+10.0.9+main.dcd20f30] {}
	at cpw.mods.modlauncher.LaunchPluginHandler.offerClassNodeToPlugins(LaunchPluginHandler.java:88) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.ClassTransformer.transform(ClassTransformer.java:120) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.TransformingClassLoader.maybeTransformClassBytes(TransformingClassLoader.java:50) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.cl.ModuleClassLoader.readerToClass(ModuleClassLoader.java:113) ~[securejarhandler-2.1.10.jar:?] {}
	at cpw.mods.cl.ModuleClassLoader.lambda$findClass$15(ModuleClassLoader.java:219) ~[securejarhandler-2.1.10.jar:?] {}
	at cpw.mods.cl.ModuleClassLoader.loadFromModule(ModuleClassLoader.java:229) ~[securejarhandler-2.1.10.jar:?] {}
	at cpw.mods.cl.ModuleClassLoader.findClass(ModuleClassLoader.java:219) ~[securejarhandler-2.1.10.jar:?] {}
	at cpw.mods.cl.ModuleClassLoader.loadClass(ModuleClassLoader.java:135) ~[securejarhandler-2.1.10.jar:?] {}
	at java.lang.ClassLoader.loadClass(ClassLoader.java:525) ~[?:?] {}
	at me.jellysquid.mods.sodium.client.SodiumClientMod.loadConfig(SodiumClientMod.java:53) ~[rubidium-mc1.20.1-0.7.1a.jar%23572!/:?] {re:mixin,re:classloading}
	at me.jellysquid.mods.sodium.client.SodiumClientMod.<clinit>(SodiumClientMod.java:22) ~[rubidium-mc1.20.1-0.7.1a.jar%23572!/:?] {re:mixin,re:classloading}
	at com.mojang.blaze3d.platform.Window.redirect$zfh000$wrapGlfwCreateWindow(Window.java:535) ~[client-1.20.1-20230612.114412-srg.jar%23644!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:rubidium.mixins.json:workarounds.context_creation.WindowMixin,pl:mixin:APP:mixins.essential.json:client.gui.Mixin_ScaleForMainMenu,pl:mixin:APP:mixins.oculus.json:MixinWindow,pl:mixin:A,pl:runtimedistcleaner:A}
	at com.mojang.blaze3d.platform.Window.<init>(Window.java:86) ~[client-1.20.1-20230612.114412-srg.jar%23644!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:rubidium.mixins.json:workarounds.context_creation.WindowMixin,pl:mixin:APP:mixins.essential.json:client.gui.Mixin_ScaleForMainMenu,pl:mixin:APP:mixins.oculus.json:MixinWindow,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.VirtualScreen.m_110872_(VirtualScreen.java:21) ~[client-1.20.1-20230612.114412-srg.jar%23644!/:?] {re:classloading}
	at net.minecraft.client.Minecraft.<init>(Minecraft.java:440) ~[client-1.20.1-20230612.114412-srg.jar%23644!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,xf:fml:xaerominimap:xaero_minecraftclient,xf:fml:xaeroworldmap:xaero_wm_minecraftclient,pl:runtimedistcleaner:A,re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,xf:fml:xaerominimap:xaero_minecraftclient,xf:fml:xaeroworldmap:xaero_wm_minecraftclient,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,xf:fml:xaerominimap:xaero_minecraftclient,xf:fml:xaeroworldmap:xaero_wm_minecraftclient,pl:mixin:APP:alexscaves.mixins.json:client.MinecraftMixin,pl:mixin:APP:dynamiclightsreforged.mixins.json:MinecraftClientMixin,pl:mixin:APP:rubidium.mixins.json:core.MinecraftClientMixin,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:mixins.oculus.json:MixinMinecraft_PipelineManagement,pl:mixin:APP:majruszlibrary-common.mixins.json:MixinMinecraft,pl:mixin:APP:fastload.mixins.json:client.MinecraftMixin,pl:mixin:APP:fallingleaves.mixins.json:MinecraftClientMixin,pl:mixin:APP:biomemusic.mixins.json:ClientMusicChoiceMixin,pl:mixin:APP:mixins.satin.client.json:event.MinecraftClientMixin,pl:mixin:APP:witherstormmod.mixins.json:MixinMinecraft,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:azurelib.forge.mixins.json:MinecraftMixin,pl:mixin:APP:mixins.essential.json:client.Mixin_RunEssentialTasks,pl:mixin:APP:mixins.essential.json:client.MixinMinecraft,pl:mixin:APP:mixins.essential.json:client.gui.Mixin_FixKeybindUnpressedInEmoteWheel,pl:mixin:APP:mixins.essential.json:client.gui.Mixin_RecalculateMenuScale,pl:mixin:APP:mixins.essential.json:compatibility.vanilla.Mixin_WorkaroundBrokenFramebufferBlitBlending,pl:mixin:APP:mixins.essential.json:feature.emote.Mixin_AllowMovementDuringEmoteWheel_HandleKeybinds,pl:mixin:APP:mixins.essential.json:feature.skin_overwrites.Mixin_InstallTrustingServicesKeyInfo,pl:mixin:A,pl:runtimedistcleaner:A}
-- Initialization --
Details:
	Modules: 
		ADVAPI32.dll:Advanced Windows 32 Base API:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		COMCTL32.dll:User Experience Controls Library:6.10 (WinBuild.160101.0800):Microsoft Corporation
		CRYPT32.dll:Crypto API32:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		CRYPTBASE.dll:Base cryptographic API DLL:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		CRYPTSP.dll:Cryptographic Service Provider API:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		CoreMessaging.dll:Microsoft CoreMessaging Dll:10.0.19041.3930:Microsoft Corporation
		CoreUIComponents.dll:Microsoft Core UI Components Dll:10.0.19041.3636:Microsoft Corporation
		DBGHELP.DLL:Windows Image Helper:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		DEVOBJ.dll:Device Information Set DLL:10.0.19041.3996 (WinBuild.160101.0800):Microsoft Corporation
		DNSAPI.dll:DNS Client API DLL:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		GDI32.dll:GDI Client DLL:10.0.19041.3996 (WinBuild.160101.0800):Microsoft Corporation
		GLU32.dll:OpenGL Utility Library DLL:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		IMM32.DLL:Multi-User Windows IMM32 API Client DLL:10.0.19041.3996 (WinBuild.160101.0800):Microsoft Corporation
		IPHLPAPI.DLL:IP Helper API:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		KERNEL32.DLL:Windows NT BASE API Client DLL:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		KERNELBASE.dll:Windows NT BASE API Client DLL:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		MSASN1.dll:ASN.1 Runtime APIs:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		MSCTF.dll:MSCTF Server DLL:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		NLAapi.dll:Network Location Awareness 2:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		NSI.dll:NSI User-mode interface DLL:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		NTASN1.dll:Microsoft ASN.1 API:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		OLEAUT32.dll:OLEAUT32.DLL:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		POWRPROF.dll:Power Profile Helper DLL:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		PROPSYS.dll:Microsoft Property System:7.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		PSAPI.DLL:Process Status Helper:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		RPCRT4.dll:Remote Procedure Call Runtime:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		SETUPAPI.dll:Windows Setup API:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		SHCORE.dll:SHCORE:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		SHELL32.dll:Windows Shell Common Dll:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		UMPDC.dll
		USER32.dll:Multi-User Windows USER API Client DLL:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		USERENV.dll:Userenv:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		VCRUNTIME140.dll:Microsoft® C Runtime Library:14.29.30139.0 built by: vcwrkspc:Microsoft Corporation
		VERSION.dll:Version Checking and File Installation Libraries:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		WINHTTP.dll:Windows HTTP Services:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		WINMM.dll:MCI API DLL:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		WINSTA.dll:Winstation Library:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		WINTRUST.dll:Microsoft Trust Verification APIs:10.0.19041.3996 (WinBuild.160101.0800):Microsoft Corporation
		WS2_32.dll:Windows Socket 2.0 32-Bit DLL:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		WSOCK32.dll:Windows Socket 32-Bit DLL:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		WTSAPI32.dll:Windows Remote Desktop Session Host Server SDK APIs:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		Wldp.dll:Windows Lockdown Policy:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		amsi.dll:Anti-Malware Scan Interface:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		apphelp.dll:Application Compatibility Client Library:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		aswAMSI.dll:Avast AMSI COM object:24.1.8821.0:AVAST Software
		aswhook.dll:Avast Hook Library:24.1.8821.0:AVAST Software
		awt.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		bcrypt.dll:Windows Cryptographic Primitives Library:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		bcryptPrimitives.dll:Windows Cryptographic Primitives Library:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		cfgmgr32.dll:Configuration Manager DLL:10.0.19041.3996 (WinBuild.160101.0800):Microsoft Corporation
		clbcatq.dll:COM+ Configuration Catalog:2001.12.10941.16384 (WinBuild.160101.0800):Microsoft Corporation
		combase.dll:Microsoft COM for Windows:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		dbgcore.DLL:Windows Core Debugging Helpers:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		dhcpcsvc.DLL:DHCP Client Service:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		dhcpcsvc6.DLL:DHCPv6 Client:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		dinput8.dll:Microsoft DirectInput:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		dwmapi.dll:Microsoft Desktop Window Manager API:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		dxcore.dll:DXCore:10.0.19041.3996 (WinBuild.160101.0800):Microsoft Corporation
		fwpuclnt.dll:FWP/IPsec User-Mode API:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		gdi32full.dll:GDI Client DLL:10.0.19041.3996 (WinBuild.160101.0800):Microsoft Corporation
		glfw.dll:GLFW 3.4.0 DLL:3.4.0:GLFW
		inputhost.dll:InputHost:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		java.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		javaw.exe:OpenJDK Platform binary:17.0.8.0:Microsoft
		jemalloc.dll
		jimage.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		jli.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		jna5540187269501251886.dll:JNA native library:6.1.4:Java(TM) Native Access (JNA)
		jsvml.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		jvm.dll:OpenJDK 64-Bit server VM:17.0.8.0:Microsoft
		kernel.appcore.dll:AppModel API Host:10.0.19041.3758 (WinBuild.160101.0800):Microsoft Corporation
		lwjgl.dll
		lwjgl_opengl.dll
		lwjgl_stb.dll
		management.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		management_ext.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		msvcp140.dll:Microsoft® C Runtime Library:14.29.30139.0 built by: vcwrkspc:Microsoft Corporation
		msvcp_win.dll:Microsoft® C Runtime Library:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		msvcrt.dll:Windows NT CRT DLL:7.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		mswsock.dll:Microsoft Windows Sockets 2.0 Service Provider:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		napinsp.dll:E-mail Naming Shim Provider:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		ncrypt.dll:Windows NCrypt Router:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		net.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		nio.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		ntdll.dll:NT Layer DLL:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		ntmarta.dll:Windows NT MARTA provider:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		nvoglv64.dll:NVIDIA Compatible OpenGL ICD:23.21.13.9135:NVIDIA Corporation
		ole32.dll:Microsoft OLE for Windows:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		opengl32.dll:OpenGL Client DLL:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		pdh.dll:Windows Performance Data Helper DLL:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		perfos.dll:Windows System Performance Objects DLL:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		perfproc.dll:Windows System Process Performance Objects DLL:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		pnrpnsp.dll:PNRP Name Space Provider:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		profapi.dll:User Profile Basic API:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		rasadhlp.dll:Remote Access AutoDial Helper:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		rsaenh.dll:Microsoft Enhanced Cryptographic Provider:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		sechost.dll:Host for SCM/SDDL/LSA Lookup APIs:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		shlwapi.dll:Shell Light-weight Utility Library:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		sunmscapi.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		textinputframework.dll:"TextInputFramework.DYNLINK":10.0.19041.3996 (WinBuild.160101.0800):Microsoft Corporation
		ucrtbase.dll:Microsoft® C Runtime Library:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		uxtheme.dll:Microsoft UxTheme Library:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		vcruntime140_1.dll:Microsoft® C Runtime Library:14.29.30139.0 built by: vcwrkspc:Microsoft Corporation
		verify.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
		win32u.dll:Win32u:10.0.19041.3996 (WinBuild.160101.0800):Microsoft Corporation
		windows.storage.dll:Microsoft WinRT Storage API:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		winrnr.dll:LDAP RnR Provider DLL:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		wintypes.dll:Windows Base Types DLL:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		wshbth.dll:Windows Sockets Helper DLL:10.0.19041.3636 (WinBuild.160101.0800):Microsoft Corporation
		xinput1_4.dll:Microsoft Common Controller API:10.0.19041.320 (WinBuild.160101.0800):Microsoft Corporation
		zip.dll:OpenJDK Platform binary:17.0.8.0:Microsoft
Stacktrace:
	at net.minecraft.client.main.Main.main(Main.java:182) ~[forge-47.2.1.jar:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:smoothboot.mixins.json:client.MainMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:111) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:99) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$makeService$0(CommonClientLaunchHandler.java:25) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:108) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:78) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}


-- System Details --
Details:
	Minecraft Version: 1.20.1
	Minecraft Version ID: 1.20.1
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 17.0.8, Microsoft
	Java VM Version: OpenJDK 64-Bit Server VM (mixed mode), Microsoft
	Memory: 929038336 bytes (886 MiB) / 1818230784 bytes (1734 MiB) up to 4294967296 bytes (4096 MiB)
	CPUs: 6
	Processor Vendor: AuthenticAMD
	Processor Name: AMD FX(tm)-6300 Six-Core Processor             
	Identifier: AuthenticAMD Family 21 Model 2 Stepping 0
	Microarchitecture: Piledriver
	Frequency (GHz): 3.51
	Number of physical packages: 1
	Number of physical CPUs: 3
	Number of logical CPUs: 6
	Graphics card #0 name: NVIDIA GeForce GT 730
	Graphics card #0 vendor: NVIDIA (0x10de)
	Graphics card #0 VRAM (MB): 4095.00
	Graphics card #0 deviceId: 0x0f02
	Graphics card #0 versionInfo: DriverVersion=23.21.13.9135
	Memory slot #0 capacity (MB): 8192.00
	Memory slot #0 clockSpeed (GHz): 1.60
	Memory slot #0 type: Other
	Virtual memory max (MB): 13106.46
	Virtual memory used (MB): 9758.91
	Swap memory total (MB): 4931.23
	Swap memory used (MB): 631.96
	JVM Flags: 4 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xss1M -Xmx4096m -Xms256m
	Launched Version: forge-47.2.1
	Backend library: LWJGL version 3.3.1 build 7
	Backend API: Unknown
	Window size: <not initialized>
	GL Caps: Using framebuffer using OpenGL 3.2
	GL debug messages: <disabled>
	Using VBOs: Yes
	Is Modded: Definitely; Client brand changed to 'forge'
	Type: Client (map_client.txt)
	CPU: <unknown>
