---
Description: The DEVINTERFACE\_XXX GUIDs are used to represent the GUIDs for device interfaces.
ms.assetid: 2503463B-D7C6-4C82-8421-424D79FD1C2A
title: DEVINTERFACE\_XXX GUIDs
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# DEVINTERFACE\_XXX GUIDs

The DEVINTERFACE\_XXX GUIDs are used to represent the GUIDs for device interfaces.

<dl> <dt>

<span id="DEVINTERFACE_AUDIO_CAPTURE"></span><span id="devinterface_audio_capture"></span>**DEVINTERFACE\_AUDIO\_CAPTURE**
</dt> <dd> <dl> <dt>



Specifies the query string used to enumerate all audio capture devices on the system. This value is returned by [**MediaDevice::GetAudioCaptureSelector**](https://msdn.microsoft.com/library/windows/apps/br226816).

Passing this value to [**ActivateAudioInterfaceAsync**](/windows/desktop/api/mmdeviceapi/nf-mmdeviceapi-activateaudiointerfaceasync) activates the requested interface on the default audio capture device.


</dt> </dl> </dd> <dt>

<span id="DEVINTERFACE_AUDIO_RENDER"></span><span id="devinterface_audio_render"></span>**DEVINTERFACE\_AUDIO\_RENDER**
</dt> <dd> <dl> <dt>



Specifies the query string used to enumerate all audio render devices on the system. This value is returned by [**MediaDevice::GetAudioRenderSelector**](https://msdn.microsoft.com/library/windows/apps/br226817).

Passing this value to [**ActivateAudioInterfaceAsync**](/windows/desktop/api/mmdeviceapi/nf-mmdeviceapi-activateaudiointerfaceasync) activates the requested interface on the default audio render device.


</dt> </dl> </dd> <dt>

<span id="DEVINTERFACE_MIDI_INPUT"></span><span id="devinterface_midi_input"></span>**DEVINTERFACE\_MIDI\_INPUT**
</dt> <dd> <dl> <dt>



Specifies the query string used to enumerate all [**MidiInPort**](https://msdn.microsoft.com/library/windows/apps/dn894770) objects on the system. This value is returned by [**MidiInPort::GetDeviceSelector**](https://msdn.microsoft.com/library/windows/apps/dn894779).


</dt> </dl> </dd> <dt>

<span id="DEVINTERFACE_MIDI_OUTPUT"></span><span id="devinterface_midi_output"></span>**DEVINTERFACE\_MIDI\_OUTPUT**
</dt> <dd> <dl> <dt>



Specifies the query string used to enumerate all [**MidiOutPort**](https://msdn.microsoft.com/library/windows/apps/dn894833) objects on the system. This value is returned by [**MidiOutPort::GetDeviceSelector**](https://msdn.microsoft.com/library/windows/apps/dn894845).


</dt> </dl> </dd> </dl>

## Requirements



|                   |                                                                                          |
|-------------------|------------------------------------------------------------------------------------------|
| Header<br/> | <dl> <dt>Mmdeviceapi.h</dt> </dl> |



 

 



