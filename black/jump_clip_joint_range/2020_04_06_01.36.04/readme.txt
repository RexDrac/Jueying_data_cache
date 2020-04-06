render-eval: False
expert-num: 4
critic-l2-reg: 0.0003
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
batch-size: 128
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
HLC-frequency: 25
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-weight-decay: 1e-06
actor-layer-size: [256, 256]
reward-scale: 0.1
actor-lr: 0.0003
critic-layer-size: [256, 256]
prioritized-exp-replay: True
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-bound-coeff: 0.0
gating-activation-fn: ['relu', 'relu', 'None']
loss-output-diff-coeff: 0
max-step-num: 2500000000
replay-buffer-size: 1000000
epoch-num: 500
max-path-num: 20
bullet-default-PD: False
env-id: HumanoidBalanceFilter-v0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-activation-fn: ['relu', 'relu', 'None']
gating-index: None
squash-action: True
gating-layer-size: [32, 32]
filter-action: True
interpolation: False
max-train-time: 10
record-start-size: 10000.0
action-dim: 12
max-path-step: 5000
total-step-num: 2500000000
imitation-weight: 0.5
loss-entropy-coeff: 0.0
tau: 0.001
expert-index: None
dsr-gait-period: 1.0
max-test-time: 10
state-dim: 23
gamma: 0.973
LLC-frequency: 500
max-episode-num: 5000000
replay-start-size: 10000
task-weight: 0.5
filter-torque: False
loss-output-smooth-coeff: 0.1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
n-step: 1
joint-interpolation: True
rollout-step-num: 1
critic-lr: 0.0003
actor-l2-reg: 0.0003
replay-ratio: 1
actor-weight-decay: 1e-06
train-step-num: 1
epoch-step-num: 5000000
test-num: 4
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
dsr-gait-freq: 1.667
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
Physics-frequency: 1000
